DENT Roadmap and Features Working Group Charter and General Process
===

# DRAFT

This Charter sets forth the responsibilities and procedures for the Roadmap and Features Working Group (RFWG), which is a working group of the TSC within the DENT project.

The activities of the RFWG will be governed by the Technical Charter, unless otherwise regulated herein. 


## 1) Mission

 a) The purpose of the Roadmap and Features Working Group is to develop and curate the list of features supported by DENT, ensuring consistency with the overarching DENT project's focus on the network edge, access, and enterprise use cases.

 b) The Roadmap and Features Working Group will be responsible for mapping out feature support and improvements to upcoming DENT releases.

 c) The Rodmap and Features Working Group will continuously evaluate and advocate for the DENT community's feature needs.

 d) The Roadmap and Features Working Group will continuously evaluate the market state and assess the feature sets of competing projects and solutions.

 e) The Roadmap and Features Working Group will consider the upstream implications of proposed features.

 f) The Roadmap and Features Working Group will provide release roadmaps to the DENT Technical Steering Committee (TSC) and the Governing Board for approval and execution.

## 2. Governance

 a) The RFWG may elect a RFWG Chair who will preside over the meetings of the RFWG and will serve until resignation or replacement. The RFWG Chair will be selected among one of the voting members of the TSC. The RFWG Chair will serve as the main point of contact between the RFWG and the TSC and will present the conclusions and proposals of the RFWG to the TSC. 

 b) TSC voting members may become members of the RFWG in case they express their interest to participate in the work of the RFWG.

 c) Participation in the RFWG is open to anyone so long as they abide by the terms of this Charter. 


## 3. New Feature/Enhancement Process

 a) Background information leading to a "feature request" may be collected in several different ways:

 i) through vendor-client interactions;
 ii) through internal DENT project focus groups; and
 iii) through various initiatives by the DENT project members.

 b) All GitHub users will be able to propose new features to the DENT project. Users will create feature requests by creating a new issue on the [Issue tab](https://github.com/dentproject/dentOS/issues) of the dentOS GitHub repository.

 c) When a feature request is submitted, the Roadmap and Features Working Group performs an initial triage discussion to determine the request's validity. All feature requests will be marked with "proposed" and "enhancement" labels. The feature's validity depends on its alignment with the DENT project mission and its value to the DENT community. The Roadmap and Features Working Group is to create and continuously update a checklist of the requirements that proposed features must meet to be considered valid.

 Once a feature is deemed valid, it will no longer hold the "proposed" label. The discussion surrounding the development of a specific feature should occur transparently in the respective GitHub issue thread. The Roadmap and Features Working Group might use additional tools (e.g., JIRA) for internal collaboration.

 d) The Roadmap and Features Working Group will perform initial research to determine if the requested features require enhancements to [switchdev-prestera](https://github.com/Marvell-switching/switchdev-prestera), [mlxsw](https://github.com/mellanox/mlxsw/) or other switchdev-related projects. The Group will use the "upstream driver enhancement" label to indicate blocking upstream issues.

 The DENT project issue tracker should not be used to track driver bugs, features, or any other improvements that are not related to feature implementation in the DENT project.

 e) The Roadmap and Features Working Group will broadly determine the systems (e.g., systemd, Linux kernel, etc.) that the proposed feature affects and whether there are additional blocking issues upstream.

 f) The Roadmap and Features Working Group will consider all known upstream implications - related to switchdev drivers or any other Open Source component - during the feature review process.

 g) The Roadmap and Features Working Group will provide a list of features requiring implementation to the DENT Technical Steering Committee (TSC). The TSC should review listed features to determine their technical feasibility, the required effort level and staffing status.

 h) The Roadmap and Features Working Group will continuously update the roadmap with the planned timing of new feature sets. The roadmap will also identify the release when a specific feature could be available (feature preview) or initially supported. A feature's inclusion on the roadmap will depend on the Technical Steering Committee's feedback regarding technical feasibility and staffing status.

 The Roadmap and Features Working Group will mark all feature request issues with a label of the expected target release.

## 4. RFWG Voting

 a) The DENT Project aims to operate as a consensus-based community, if any RFWG decision requires a vote to move the Project forward, the members of the RFWG will vote on a one vote per member basis.

 b) Quorum for RFWG meetings requires at least fifty percent of all members of the RFWG to be present. The RFWG may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.

 c) Except as provided in Section 5, decisions by vote at a meeting require a majority vote of those in attendance, provided quorum is met. Decisions made by electronic vote without a meeting require a majority vote of all members of the RFWG.

 d) In the event a vote cannot be resolved by the RFWG, any member of the RFWG may refer the matter to the TSC for assistance in reaching a resolution.

## 5. Amendments

 a) This charter may be amended by a two-thirds vote of the entire RFWG and is subject to approval by the TSC.

# DRAFT
