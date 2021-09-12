# COOS Governance

draft v0.2

## Scope

COOS governance is fully in line with the ModernStats Governance Guidance, the generic governance applicable to all ModernStats models. The COOS governance contains additional and COOS-specific elements to this generic governance. Please consult the ModernStats Governance Guidance first as the two documents together cover the full governance for COOS. [add link to the ModernStats governance document later]

## Versioning

Based on the common semantic versioning governance elements of the ModernStats models [link], the following COOS-specific rules apply to the three main version types:

 - Major: there are changes in the new version that affect the formal naming, definitions and descriptions of the existing concepts, as well as the relations between these concepts.

 - Minor: there are changes of concepts and/or relations of the model that do not affect the formal naming, definitions and descriptions. The changes might include adding new concepts or relations or removing old ones, but all of these changes are considered as backward-compatible with the existing model.

 - Patch: error corrections, textual or visual changes based on errors identified in previous versions that result in backwards-compatible bug fixes. Changes implemented as part of the patch do not change the substance.

## COOS design principles

<table>
  <thead>
    <tr>
      <th scope="col" align="center">N°</th>
      <th scope="col" >Principle</th>
      <th scope="col" >Statement</th>
      <th scope="col" >Rationale</th>
      <th scope="col" >Implications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	  <th scope="row">1</th>
      <td><b>Change control</b></td>
      <td><p>COOS has change control i.e. the design principles of COOS apply to national adaptation of COOS and to the revisions of the model.</p></td>
      <td>
        <p>The only way to provide a consistent level of quality information to users is if the whole organisation abides by the same principles. Therefore, it is recommended that local adaptations of COOS apply the design principles.</p>
        <p>The design principles also need to be used for future revisions of COOS in order to ensure consistency and comparability between different versions.</p>
      </td>
      <td>
        <ul>
          <li>COOS adaptation/revision initiatives will not begin until they are examined for compliance with the design principles. A conflict with a principle will be resolved by changing the framework of the initiative.</li>
          <li>Mechanisms are needed to monitor the implementation of COOS and adapt it where necessary to meet business needs.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">1</th>
      <td><b>Use of agreed standards</b></td>
      <td><p>COOS is built upon foundations set by other standards, makes use of already available standards and helps the user to leverage them in combination.</p></td>
      <td>
        <p>COOS provides a formal presentation of all ModernStats standards covering the statistical business process, the information objects and the generic activities of statistical organisations.</p>
        <p>COOS is also linked to general vocabularies, data models and existing ontologies, such as DCAT, PROV, SKOS</p>
        <p>By COOS providing the high-level formal presentation of the concepts used in these models, it is ultimately connecting them.</p>
      </td>
      <td>
        <ul>
          <li>COOS adaptation/revision initiatives will not begin until they are examined for compliance with the design principles. A conflict with a principle will be resolved by changing the framework of the initiative.</li>
          <li>Mechanisms are needed to monitor the implementation of COOS and adapt it where necessary to meet business needs.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


## Process of reviewing/designing COOS

The process of the COOS describes the full procedure for the establishment of the COOS, starting with specifying the needs. It describes how COOS is developed and maintained by the owner of the model. The process consists of 5 mind process steps broken down by sub-processes (see Figure 1).

Source: https://ec.europa.eu/eurostat/cros/content/ess-standardisation (modified for COOS use).

It does not cover the process of adoption by National Statistical Offices as that activity might vary from NSO to NSO.

This process model for ontology also includes the iterative approach similar to the PDCA cycle of quality management as ensuring the quality of an ontology is of high importance to serve user needs.

## COOS Decision principles

In order to keep the creation and update of the COOS understandable, some main criteria are defined in order to help NSOs with adopting COOS or a national ontology.

### Summary of the five steps

#### 1. Specify needs for ontology creation and update

The step of the COOS begins with collecting the needs from different stakeholders. Mainly stakeholders are NSOs as a part of the international statistical community. The need might come from changing connecting models (GSBPM, GSIM etc.) or can be derived from the demand of HLG as well. This collection of needs is in line with the Capability Development activity area of GAMSO and the process phase of Specify needs of GSBPM where modification of existing statistical outputs or new needs for new statistical outputs (as GSIM information objects) might come into consideration. This step takes input from the continuous communication with stakeholders. This step ends with the approval of the proposal on the COOS update. This approval has to be made by experts on ontologies and the stakeholders. This process is the task of the Supporting Standards Group.

#### 2. Design updates to the ontology

This step covers the compilation of ontology specifications based on the approved proposal of the previous step ’Specify needs for ontology update’. The compilation of the specification of the COOS means determining the methodological background of the ontology such as basic terms that have to be used when compiling statistical outputs, the planning of the structure and their detailed content needed for the outputs and an implementation plan. This implementation plan is only for the COOS of statistical products of the owner of the standard and not for NSO level. The NSO-level adoption is not in the scope of this process. Compiling documents of ontology design, the drafting is the task of the Supporting Standards Group.

#### 3. Build ontology
This step covers the programming of the ontology prepared in the ’Design (new version) of the ontology’ step. This step ends with the compilation of a draft proposal for adoption, including the programmed ontology and an implementation plan mentioned in the previous step.  The drafting is the task of the Supporting Standards Group.

#### 4. Adoption of the ontology
In order to support the formal adoption of COOS the output of the step Build Ontology is presented to the stakeholders and the feedback is collected in the form of an expert review and a public review. After stakeholder consultations the final proposal is submitted to HLG-MOS for adoption. In case of a positive decision, the new version of the COOS is released.

#### 5. Support and Community Management of the ontology
Between review cycles of the ontology, the use of the model by the community is monitored and feedback is encouraged, lessons learnt are collected from the community. In order to foster the use of the model, supporting material (learning and communication) is provided. Periodic checks are conducted from time to time to have an up-to-date overview on the use of the model. Based on this overview and feedback from stakeholders, the team behind the ownership of COOS evaluates if a revision is needed and if so, an activity proposal is prepared and the revision process is launched in the form of a Task Team.

### Detailed description of process

#### 1. Specify needs for ontology creation and update

##### 1.1. Determine the scope

##### 1.2.	Enumerate important terms

##### 1.3. Proposal on the COOS creation and update

##### 1.4. Approval of the proposed changes

#### 2. Design updates to the ontology

##### 2.1. Exploration of existing ontologies

##### 2.2. Define the classes and hierarchy

##### 2.3. Define the properties of classes-slots

##### 2.4. Define the facets of slots

##### 2.5. Compiling document of ontology design

#### 3. Build ontology

##### 3.1. Create instances

##### 3.2. Ensuring that the class hierarchy is correct

##### 3.3. Configure workflow

##### 3.4. Test COOS Ontology

##### 3.5. Finalise COOS Ontology

##### 3.6. Draft proposal on the adoption

#### 4. Adoption of the ontology

##### 4.1. Stakeholder consultation: expert review

##### 4.2. Stakeholder consultation: public review (optional)

##### 4.3. Ratification

#### 5. Support and Community Management of the ontology

##### 5.1. Maintenance of the ontology

##### 5.2. Monitor use of the ontology

##### 5.3. Activity proposal on the revision

##### 5.4. Approval of the activity proposal for ontology update

##### 5.5. Launch of a Task Team responsible for the revision
 
