---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
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
  /assistance/v1/home/water_damage/declarations/{declaration_id}:
    patch:
      summary: Updates information related to the water damage declaration
      description: Updates information related to the water damage declaration
      operationId: patchAssistanceV1HomeWater_damageDeclarationsDeclaration_id
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-id-patch
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
      - information
      - related
      - to
      - the
      - water
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the water damage declaration
      description: Updates the policy holder information of the water damage declaration
      operationId: patchAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - water
      - damage
      - Declarations
---