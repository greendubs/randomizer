# randomizer
A novel way to anonymize and keep track of survey responses


# Concept 

An open source tool to randomize and anonymize responses from a set of predetermined users. The tool should give an accurate count of how many people have responded to a survey (response question) and how many have not responded, while ensuring that the responses of individual users are security protected and anonymized.

# Workflow

1. A user (data collector) creates an email invite to 5 users (data senders) for a response on a URL
2. All data senders receive an email, but only 3 click on the URL to submit a response.
3. The collector can see that 2 respondents have not responded to the survey, but their identity is hidden.
4. The collector can send an email response/reminder to those who have not responded.
5. Once the remaining 2 responses are completed, the survey closes automatically and generates a result.

# Out-of-Scope:

No front end work, email notifications, etc.

# In-Scope

1. Only complete back-end algorithm work in Python
2. Demo an algorithm in python to ensure that there is no way for anyone to check the responses of any data collector, but we can count only who has responded and who hasn’t. 
3. The identity of who has responded OR not responded should always be hidden/anonymized. There should be no way to track back the responses back to the respondents.
