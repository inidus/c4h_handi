# Ehrscape Domain

### What has been pre-prepared

1. An inidus Ehrscape domain which allows you to control your own patient data and clinical content models.

2. Access to the Marand [EhrExplorer](https://test.operon.systems/explorer) view of your domain. This will allow templates to be viewed and Archetype Query Language (AQL) queries to be constructed.

3. A [Workspace.md](/docs/workspace.md) file containing details of key domain identifiers and assets e.g. dummy patient identifiers, template names, login and password details for your domain.

4. A [local repository](/models) of openEHR clinical content models (archetypes and templates. These archetypes and templates have assembled partly from remote repositories such as the [openEHR Foundation CKM](http://openehr.org/ckm) repository, or [Apperta UK Clinical Models](http://ckm.apperta.org.uk/ckm) repository. Other artefacts, in particular the openEHR templates, have been authored locally and are maintained along with copies of the required archetypes in this Git repository.

	The ‘operational templates’ (effectively the compiled version 	of each template) have been uploaded to your domain along with some dummy data.

The templates are most easily viewed via the Marand [EhrExplorer](test.operon.systems/explorer) tool.

5. A [Postman](https://www.getpostman.com/) [Collections](/docs/domain/openEHR_Ehrscape.postman_collection.json) file which can be imported to provide easy access to the Ehrscape API.

6. A [Postman](https://www.getpostman.com/) [Environment](/docs/domain/C4H_Domain.postman_environment) file for your domain, containing a number of preset environment variables. If you have been supplied with your own Envionment file you should use that instead.

7. A [Technical guide](/docs/scenarios/tech_guide.md), describing the key tasks involved in getting up and running with Ehrscape.

8. An [Overview of openEHR and Ehrscape guide](/docs/openehr/openehr_intro.md) for those new to openEHR concepts.

9. A [Ehrscape API Reference Guide](https://dev.ehrscape.com/documentation.html) with detailed descriptions of the calls.
