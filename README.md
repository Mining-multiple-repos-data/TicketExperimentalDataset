# Qualitative Study
Process mining ITIS ticket data to improve resolution time.

- ActivitiesList.docx: List of activities captured for the ticket lifecycle along with the description of activities.
- UserSurvey.docx: It is the survey questionnaire send to users to understand their experience with ITIS ticket reporting in last six months.
- UserResponses.xlsx: Consolidated responses for user survey.
- processmap.pdf: Process map for complete process derived using Disco, a process mining framework. Shade of node corresponds to frequency of activity, edge thickness corresponds to frequency of transition and map is annotated with SLA state (resume/pause).
https://cloud.githubusercontent.com/assets/6483834/8085621/5dc60c84-0f91-11e5-8468-c583673506f4.gif
- AnalystSurvey.docx: It is the survey questionnaire send to analysts to understand their experience with ITIS ticket resolution in last six months.
- AnalystResponses.xlsx: Consolidated responses for analyst survey.
- regex_for_information_needs.docx: Keywords used for annotating comments with the information asked to train the preemptive model.
- Dictionary.docx: Regular expressions used to identify different types of tactical user input requests. Example: Temporize, ContactMe, Transfer, DoneSoCheck
- stopWords.txt: List of stop words for preprocessing ticket data
- Code for preemptive model is available at https://github.com/Mining-multiple-repos-data/PreemptiveCode
- annotationUI_screenshot.docx: Screenshot for the tool designed to manually label user input request comments
