---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Adds contact information of the water damage declaration
  description: Adds contact information of the water damage declaration
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information related to each the policy holder of the water
        damage declaration
      description: Gets the information related to each the policy holder of the water
        damage declaration
      operationId: getAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - related
      - to
      - each
      - the
      - policy
      - holder
      - of
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations:
    post:
      summary: Creates a declaration for a water damage
      description: Creates a declaration for a water damage
      operationId: postAssistanceV1HomeWater_damageDeclarations
      x-api-path-slug: assistancev1homewater-damagedeclarations-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - CreatesDeclarationsa
      - water
      - damage
  /assistance/v1/home/water_damage/declarations/{declaration_id}/contacts:
    post:
      summary: Adds contact information of the water damage declaration
      description: Adds contact information of the water damage declaration
      operationId: postAssistanceV1HomeWater_damageDeclarationsDeclaration_idContacts
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idcontacts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - contact
      - information
      - of
      - the
      - water
      - damage
      - Declarations
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---