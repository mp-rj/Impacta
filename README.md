# Impacta
***Open innovation for solving public sector challenges***

*Para Português, clique [aqui](https://github.com/mp-rj/Impacta/blob/master/LEIAME.md).*

**Nobody innovates alone**. There is an enormous potential for solving complex government challenges when the path to collective intelligence is paved. This is the promise of open innovation, a process that subverts the traditional logic of many government buying decisions. Instead of specifying the desired solution, the public agency defines the challenge and the expected result, guaranteeing society - Academia, companies, start-ups etc. - the opportunity to co-create solutions. When it comes to digital solutions and new technologies, the potential for open innovation is even greater.

**Impacta** is an experimental open innovation project from the Innovation Lab of the State Prosecutor's Office of Rio de Janeiro (Inova_MPRJ). Its objective is to explore and test cutting edge practices in open innovation for governments - considering experiences in Brazil and abroad. With the lessons from this program, Inova_MPRJ hopes to suggest new public purchasing practices and policies, strategic planning and partnerships - not only for MPRJ, but for any and all government agencies. We also expect to produce proposals that may improve the regulatory environment for innovation.

## What do I find in this repository?
The innovative approach in this program begins in its initial steps. We are building the first version and will conduct MPRJ's inaugural open innovation cycle in a collaborative and 100% transparent manner. We seek to reach the maximum level of compliance with **[Open Contracting Partnership (OCP)](https://www.open-contracting.org/)** data standards  - something [unprecedented](https://web.archive.org/web/20200404154540/https://www.open-contracting.org/worldwide/) in Brazil.

In this repository, you will find the entire record of hiring the program, since the hiring of the accelerator that will manage the program. All files are in JSON format and are compatible with the [Open Contracting Data Standard (OCDS)](https://standard.open-contracting.org/latest/en/) version 1.1. In the [records](https://github.com/mp-rj/Impacta/blob/master/records) folder it is possible to find the consolidated record with the latest information on contracts, while the [release-packages](https://github.com/mp-rj/Impacta/blob/master/release-packages) folder contains all the update history related to these processes. Information regarding the following processes is available in these folders:
- **ocds-e5r943-2020000234749**: contracting process of an Accelerator to manage the MPRJ's open innovation program (Impacta).


## How to use the data
The Open Contracting Partnership maintains a [repository of reusable tools](https://airtable.com/shrzycSNYRcmV0WSZ/tblhHNGcDXuievZ74?blocks=hide) to analyze and present OCDS-compatible data. We also recommend visiting their [project gallery](https://airtable.com/shrsJ2QRVrpUaUWLf/tblhHNGcDXuievZ74?blocks=hide), where you can get inspired by different solutions proposed around the world using open contracting data.


## Contributing
If you are interested in MPRJ's open innovation program and want to learn more about it, visit [Impacta's website](https://www.mprj.mp.br/inova/impacta). There, you will find the latest news on the project, including how to participate.

If you are also interested in open contracting and have an idea to promote this agenda in Rio de Janeiro and in Brazil, get in touch with us, by sending an e-mail: [inova@mprj.mp.br](inova@mprj.mp.br). We are always seeking new partnerships!

If you have some specific observation about the data in this repository or about our implementation of the OCDS, you can also send us an e-mail - or, alternatively, [open an Issue](https://github.com/mp-rj/Impacta/issues) here on GitHub. We will try to answer you as soon as possible.


## Publication policy

### Who is responsible for providing the data here?
Inova_MPRJ is responsible for updating any information about the program and its contracting processes. The easiest way of contacting the Lab team through the e-mail address: **[inova@mprj.mp.br](mailto:inova@mprj.mp.br)**. If you prefer, you may also visit us at [Av. Mal. Câmara, 370 - 4º andar - Castelo, Rio de Janeiro, RJ](https://www.openstreetmap.org/node/7184338297).

### Where does the data here come from? How often is it updated?
Data in this repository should mirror the main aspects of the related administrative proceedings. However, there is currently no automated extracting tool from MPRJ's process management systems. For the time being, new releases will be generated manually by the Lab team, whenever possible with updates before and after the main milestones of the contracting process: release of the Contracting Plan Daft, release of the Term of Reference, publishing of the tender Notice, opening of the bids, contracting and execution of the project main milestones.

### Exceptions to data disclosure
There is no confidentiality hypothesis fixed for the contracting processed involved in Impacta program. However, [Brazilian Bill on Public Tenders and Contracting](https://www.lexml.gov.br/urn/urn:lex:br:federal:lei:1993-06-21;8666) does impose confidentiality on the content of the bids until the tender date. 

The disclosure of contracting processes **does not extend** to the detailed content of the solutions proposed during the open innovation program. The contracting process shall fix specific clauses on the intellectual property of these solutions, which may include commercial and/or industrial confidentiality hypotheses. The same is true for data transferred by MPRJ to the program participants, as they may be subject to specific policies on personal and/or confidential data protection.

### Adaptions to the standard codelists and internationalization approach
The implementation of the Open Contracting Data Standard for the Impacta program should be considered experimental. We are working with all the tools offered by OCP to guarantee total interoperability with the tools that use this standard. Even so, some adaptations are likely to be necessary to deal with the Brazilian regulations and the specificities of the program itself.

Some points the user might want to consider when consuming the data are:
- The files are generated with OCDS properties named in English, as there is no current translation of the standard for Portuguese. The main language for the properties values, on the other hand, is Brazilian Portuguese. Names, descriptions and other free text properties are often translated also to English, indicated by the property suffix "_en".
- Presently, OCDS recommends using [org-id](http://org-id.guide/) codelists to identify the contracting parties. However, this repository does not include the main identifiers used in Brazil, such as the Natural Persons Registry (CPF) and the National Registry of Legal Entities (CNPJ) (even though there is an [open proposal on that](https://github.com/org-id/register/issues/365)). While the organization responsible for maintaining org-id [is not accepting new, unsolicited entries](https://github.com/org-id/register/tree/ee6179b02071c60e516202635a94e0b6782cf6e9#current-status-as-of-18th-december-2019), we have used the OCDS prefix to identify the parties (preferably), or the unofficial "BR-CNPJ" - or "BR-CPF" - codes, which refer to [registries from Secretaria da Receita Federal do Brasil](http://receita.economia.gov.br/orientacao/tributaria/cadastros). 
- The unit codelists recommended by OCDS to quantify the items in the tenders - that is, [UNCEFACT](http://www.unece.org/fileadmin/DAM/cefact/recommendations/rec20/Rec20rev14e-Annex_II-III_2020.xls) and [QUDT](http://www.qudt.org/qudt/owl/1.0.0/unit/Instances.html) - are appropriate mainly for physical goods. These codelists offer few options for quantifying services, which are most of the contracts in the Impacta program. Follow the premise of [publishing early, and improving disclosure step-by-step](https://standard.open-contracting.org/latest/en/#open-contracting-data-standard-documentation), we have launched the first releases without any quantity defined according to the standard. We [welcome suggestions](#contributing) on how to deal with this matter.

### Plans for improving data quality
Next steps to improve the transparency of the program and the compatibility with open data standards and best practices include:
- Solving the matter on quantifying services ([see above](#adaptions-to-the-standard-codelists-and-internationalization-approach));
- Presenting structured data with all the comments receiver during the period for public consultation on the [Contracting Plan Draft](https://drive.google.com/file/d/1qQPijADRnhI37EY16_HM0QksOasKaMI2);
- Keeping the repository updated with the latest news on the innovation Accelerator contracting;
- Stimulating the adoption of open contracting standards among other public sector bodies in Brazil, as well as their use by the civil society and by private firms. 
