# Data Dictionary

## Overview
This dataset contains responses from a survey of University of Virginia students about hot dog preferences and opinions.
Each row represents one survey respondent.

| Variable Name | Description | Type | Possible Values / Range | Units | Notes |
|--------------|------------|------|-------------------------|-------|------|
| Timestamp | Date and time when the survey response was submitted | Datetime | ISO datetime values | N/A | Used to track when responses were collected |
| Year at UVA | The respondent’s academic year at the University of Virginia | Categorical | First Year, Second Year, Third Year, Fourth Year, Graduate, Other | N/A | Self-reported |
| What is your Gender Identity? | The respondent’s self-identified gender | Categorical | Male, Female, Non-binary, Prefer not to say, Other | N/A | Responses may be cleaned or standardized |
| What Schools are you a Part of? | The UVA school(s) the respondent belongs to | Categorical (multi-select) | College of Arts & Sciences, Engineering, McIntire, Nursing, Education, etc. | N/A | Some responses contain multiple schools |
| Is a Hotdog a Sandwich? | The respondent’s opinion on whether a hot dog counts as a sandwich | Categorical | Yes, No, Unsure | N/A | Used as the main opinion variable |
| How strongly do you feel about your previous answer? | Strength of opinion about whether a hot dog is a sandwich | Ordinal categorical | Very weak, Weak, Neutral, Strong, Very strong | N/A | Ordered scale |
| How frequently do you eat hot dogs? | How often the respondent eats hot dogs | Ordinal categorical | Never, Rarely, Monthly, Weekly, Daily | N/A | Ordered frequency scale |
