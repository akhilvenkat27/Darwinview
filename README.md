# Darwinview
`Darwinview` is an Intelligent Interview System(IIS) that enables a high-end 1:1 interview experience in the assessments.     
>More formally even if the recruiter makes the wrong hire mistake AI won't.

Foremost let us take a quick look at the ' traditional 1:1 interview system ', in the below diagram.

```mermaid
graph TD;
    Assessment_Platform  --> Recruiter;
    Assessment_Platform  --> Candidate;
    Recruiter --> Sends_Interview_Request_to_Candidate;
    Sends_Interview_Request_to_Candidate --> Receives_Interview_Invitation;
    Sends_Interview_Request_to_Candidate --> Generate_Results;
    Candidate --> Receives_Interview_Invitation;
    Receives_Interview_Invitation --> Attempt_Coding/Hr_Interview;
    Attempt_Coding/Hr_Interview --> Detecting_Face/similar_For_Candidate_Genuinity;
    Detecting_Face/similar_For_Candidate_Genuinity --> Test_End;
    Test_End --> Sends_Interview_Request_to_Candidate;
```
 Here is a glance at ` Darwinview `  which is enhanced with AI to automate interview experience.

```mermaid
graph TD;
    Darwinview  --> Recruiter;
    Darwinview --> Candidate;
    Recruiter --> Sends_Interview_Request_to_Candidate;
    Sends_Interview_Request_to_Candidate --> Receives_Interview_Invitation;
    Sends_Interview_Request_to_Candidate --> Recommends_Topics/Questions_need_to_cover_in_Interview_based_on_Role;
    Recommends_Topics/Questions_need_to_cover_in_Interview_based_on_Role --> Gets_Candidate_Test_statistics;
    Recommends_Topics/Questions_need_to_cover_in_Interview_based_on_Role  --> Attempt_Coding/Hr_Interview;
    Gets_Candidate_Test_statistics --> Generate_Results;
    Candidate --> Receives_Interview_Invitation;
    Receives_Interview_Invitation --> Attempt_Coding/Hr_Interview;
    Attempt_Coding/Hr_Interview --> Detecting_Face/similar_For_Candidate_Genuinity;
    Detecting_Face/similar_For_Candidate_Genuinity --> Extracts_Speech_from_Candidate_and_Recruiter;
    Extracts_Speech_from_Candidate_and_Recruiter --> Measures_Answer_Relavance_Percentage_for_Recruiter_Question;
    Measures_Answer_Relavance_Percentage_for_Recruiter_Question --> Measures_Candidate_Confidence_Rate,Correctness,Average_Answer_Rate;
    Measures_Candidate_Confidence_Rate,Correctness,Average_Answer_Rate --> Recommends_topics/suggestions_needed_to_focus_on_for_Candidate;
    Recommends_topics/suggestions_needed_to_focus_on_for_Candidate --> Interview_Ends;
    Interview_Ends --> Generate_Results;
```
> [!TIP]
> If you want to take a look at the full picture of the online recruitment process, Visit Here https://bit.ly/DarwinBox_Assessments.

<summary>Sailent Features of Darwin-View</summary>  
</br>  

- [X] Creates Assessment Platform for 1:1 Interview Session.  
- [X] Extract speech from the candidate  which is answered, Extract speech from the recruiter as well, and outputs the answer relevance rate for the total interview from the candidate data.  
- [X] Includes candidate confidence rate, average answer speed, correctness, test statistics, etc.
- [X] Recommends the improvements/skills to work on from interview to candidate.
- [X] Recommend topics to the recruiter that have to be cover in the interview based on role.

