# Call for Tools Papers

The ICAPS 2025 Program Committee have introduced a new type of submission that follows the example of conferences
such as [TACAS](https://etaps.org/2024/conferences/tacas/) and [CAV](https://i-cav.org/2024/call-for-papers/) to
encourage and reward with visibility community efforts towards developing, maintaining and extending publicly
available tools that enable and facilitate research into planning and scheduling.

It is common place that submissions to ICAPS include a brief section discussing implementation and engineering issues.
The purpose of introducing a specific type of submissions with slightly different instructions to the rest is to put
into focus the engineering issues in a self-contained and autonomous fashion, separate from contributions that focus
on algorithms, theory or representations. 

Doing so provides useful context to evaluate novelty of submissions. The subject of Tools papers can be refinements 
or optimizations of existing algorithms or techniques. Therefore, these submissions may not be novel from a theoretical 
or algorithmic perspective, but may well be so from an engineering perspective and have wide-ranging, long-standing 
impact. 

For instance, the "two-literal watch rule" was not a significant innovation
from a theoretical or algorithmic perspective, but its introduction along with other important techniques, had 
profound impacts in the applications and direction of research in Boolean Satisfiability.

## Specific Instructions for Tools Papers

Submissions must describe tools of broad interest and utility to the ICAPS community.

Papers in this category must clearly describe the problem to be solved, its importance, related work, the techniques 
used in the tool and their novelty, the construction of the tool, its unique features, discuss how the tool is used 
and present benchmarking of the tool including comparisons with other tools and previous versions of the tool. For 
tools from the industry, the description should be useful in allowing the community members to reproduce some of the key 
techniques or “tricks” in their own tools.

Tools papers are required to provide an "artifact" along with a paper (either long or short) whose format and content
satisfies the requirements given in the [Call for Papers](/calls/main_track). Arfifacts are defined as additional
material (software, data sets, etc.) that substantiates claims made in the paper and renders them **fully replicable**.
An artifact may for instance consist of a tool and its accompanying documentation, the input files used for the 
evaluation of the tool in the paper, and configuration files or other documents that describe the parameters used in 
the experiments. 

Reviewers are instructed to read the corresponding paper and evaluate the artifact according to the following criteria
included in our [instructions for reviewers](/organisation/roles_and_guidelines):
 - consistency with and replicability of results presented in the paper,
 - completeness,
 - documentation and ease of use,
 - availability in a permanent online repository.

There is no requirement of anonymising the artefact, so these submissions are de-facto **single-blind**. Still, we
expect that the paper submitted for review satisfy the requirements of double-blind review outlined in the 
[Call for Papers](/calls/main_track).

## Artifact Submission

Artifacts must be submitted as part of the Supplementary Materials section in the OpenReview submission form. The following
items must be found in the ZIP archive submitted as supplementary materials:

 - an abstract that summarises the artifact and its relation to the paper,
 - a license document (LICENSE) for the artifact that must, at the very least, allow the assigned PC members to evaluate the 
   artifact,
 - an instructions document (README) that includes:
   - a hyperlink to the artifact,
   - a description of additional requirements for the artifact, such as installation of proprietary software or particular
     hardware resources,
   - detailed instructions that enable the PC to quickly verify that the artifact is running properly,
   - detailed instructions for using the artifact to replicate the results in the paper, including estimated resources
     if these are non-trivial.

The artifact hyperlink must point to a service or repository that allows interaction with or downloading the artifact
in a **completely anonymous fashion**. Failure to do so, or active attempts to identify the PC members reviewing the 
artifact, will lead to **summary desk rejection**.

