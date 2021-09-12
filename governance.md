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
	  <th scope="row">2</th>
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
    <tr>
	  <th scope="row">3</th>
      <td><b>Stakeholder appeal</b></td>
      <td><p>COOS helps stakeholders to understand various standards and their connections.</p></td>
      <td>
        <p>COOS helps stakeholders to easily understand the importance of different standards and their connections in order to realise what benefits can be expected from their use.</p>
      </td>
      <td>
        <ul>
          <li>COOS ultimately means having an integrated view in place in the future on the ModernStats models, the ontology standards and their connections. This is important for their further development and more active stakeholder involvement. COOS will therefore be a powerful way to explain to stakeholders on a high level how the different standards and models are connected.</li>
          <li>The intuitive appeal of the model should be tested with all targeted stakeholder groups. The value increases proportionally with the number of stakeholders who adopt the model.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">4</th>
      <td><b>Driver for modernisation and future revisions</b></td>
      <td><p>COOS is powerful in suggestingfuture modernisation and initiating revisions of the involved standards.</p></td>
      <td>
        <p>COOS provides ideas for future modernisation activities.</p>
        <p>With COOS connecting several models and standards, it will also be used as a guidance on how to improve each  and strengthen the interconnection between them to have better integration in the future.</p>
      </td>
      <td>
        <ul>
          <li>COOS will help the community to identify further modernisation activities to better integrate standards used in the domain of official statistics and existing ontology standards.</li>
          <li>Whenever ModernStats standards are to be revised or further developed, COOS will be used as one of the inputs to identify areas and priorities for their revisions.</li>
          <li>In the longer run, the use of COOS will also help to synchronize revision practices for each involved standard.</li>
          <li>Whenever ModernStats models are developed or further developed, COOS implications will have to be taken on board for discussions.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">5</th>
      <td><b>Simple presentation</b></td>
      <td>
        <p>COOS objects and their relationships are presented as simply as possible.</p>
		<p>COOS is aimed to provide a generic solution to users and not specific elements for different statistical domains.</p>
	  </td>
      <td>
        <p>Even though the use of ontology standards will ensure that the information described by COOS is understandable, it needs to be presented as simply as possible, avoiding notations and presentation styles that are known only to experts.</p>
      </td>
      <td>
        <ul>
          <li>COOS will not be widely adopted if it cannot be easily understood by different stakeholders.</li>
          <li>Presentations using specific formats can be too technical for most stakeholders, therefore a non-technical presentation is needed for the wide audience.</li>
          <li>For specific purposes, precise presentation in OWL format should also be provided.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">6</th>
      <td><b>Agreed level of detail</b></td>
      <td>
        <p>COOS represents objects only down to the level of agreement between key stakeholders.</p>
	  </td>
      <td>
        <p>COOS does not represent information on the deep level of the standards but on high-level to highlight the benefits of using different models together.</p>
        <p>Too detailed level means the presentation will not be easy for several stakeholders to adopt/understand while too high-level imposes the risk of not realising the benefit of each standard.</p>
      </td>
      <td>
        <ul>
          <li>COOS must adhere to an appropriate, agreed level of detail in order to remain generic.</li>
          <li>Stakeholders must agree on what the appropriate level of detail for COOS is.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">7</th>
      <td><b>Adaptability and extensibility</b></td>
      <td>
        <p>COOS can be easily adapted and extended to meet new/changed user needs.</p>
	  </td>
      <td>
        <p>COOS will need to be robust and stable to be adopted by statistical organizations, but will need ongoing review and adaptation to remain relevant to user needs.</p>
      </td>
      <td>
        <ul>
          <li>During the design of ontology, each organisation should identify how and in what context it will adapt it to its own use. Different national environments might define different requirements for this purpose.</li>
          <li>Mechanisms for ongoing review and update will need to be established.</li>
          <li>Users will need incentives to test initial versions of COOS so that it can be adapted to meet a variety of needs.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">8</th>
      <td><b>Platform independence</b></td>
      <td>
        <p>COOS does not refer to any specific IT setting or tool.</p>
	  </td>
      <td>
        <p>Statistical organizations use a wide range of in-house and proprietary hardware and software platforms; this environment also changes over time. COOS must be platform independent to be relevant to all stakeholders and robust over time.</p>
        <p>COOS will provide the ontology based on ModernStats standards and common ontology models. The interpretation, presentation is not IT-specific, the formats used for the ontology do not limit its use in specific IT settings.</p>
      </td>
      <td>
        <ul>
          <li>COOS needs to be designed to be a generic connecting model, using a standard language.</li>
          <li>COOS will be available as OWL format to further facilitate machine interpretability of content but it will not limit the use of ontology on different platforms.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">9</th>
      <td><b>Formal specification</b></td>
      <td>
        <p>COOS provides formal naming, definitions and descriptions of  concepts in a given domain, and the relationships between these concepts.</p>
	  </td>
      <td>
        <p>COOS will provide a set of standardized, consistently described objects (OWL). This will help readers understand significant relationships among the objects in the various standards involved in the ontology.</p>
      </td>
      <td>
        <ul>
          <li>In the field of official statistics, a number of models, vocabularies or other semantic assets already exist, but they are often not formally expressed or coherent with one another. The ontology can help an organisation with this integration.</li>
          <li>The method used to specify COOS should be transparent to those not involved in the development of COOS.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">10</th>
      <td><b>Reusability</b></td>
      <td>
        <p>COOS is meant for repeated use and not only for a one-time investment.</p>
	  </td>
      <td>
        <p>Development of COOS requires stocktaking of standards to be involved in the work according to the user needs.</p>
        <p>Once it is developed, it needs to be put in use in order to realise its benefits in harmonisation and modernisation goals. The developed solution can be used and reused by the organisation.</p>
      </td>
      <td>
        <ul>
          <li>COOS should be designed and developed with the motivation to be used in practice. Only with its repeated use can most of its benefits be realised by the organisation.</li>
          <li>COOS should be designed in a way that the needs for its reuse are collected and analysed to ensure smooth transition from development to implementation phase.</li>
        </ul>
      </td>
    </tr>
    <tr>
	  <th scope="row">11</th>
      <td><b>Relevance</b></td>
      <td>
        <p>COOS is a solution that provides relevant information on the standards and their relationships to the users.</p>
	  </td>
      <td>
        <p>The ontology in itself is an up-to-date solution but it also means that the information described by the ontology is relevant to the users and outdated information is removed, new information is added. COOS represents the latest versions of the underlying models it is integrating, e.g. GSIM, GAMSO, etc.</p>
      </td>
      <td>
        <ul>
          <li>Representing outdated information or using not up-to-date ontology standards by the COOS means loss of interest by stakeholders.</li>
          <li>Attention should be given to its maintenance and future revisions during the development of COOS in order to ensure its relevance.</li>
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
 
