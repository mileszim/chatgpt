Write an example of a multi-step prompt for ChatGPT. It should involve 3-5 steps. Each step should query the user for more information or context, with the final step response returning the result that the info was needed for.

The prompt should be in the format:

```
# Prompt

[prompt instructions].

[step execution instructions; example=“”]

# Steps

1. Ask the user: "Question 1/8: How much do you earn per fortnight?”. Wait for the user's response.
2. Ask the user: "Question 2/8: What is your weekly rent or mortgage cost?”. Wait for the user's response.
3. Ask the user: "Question 3/8: How much do you spend on groceries per week?". Wait for the user's response.
4. […remaining steps]

# Response

[formatted instructions for the response. example=“Once all {# of steps} questions have been asked, create a markdown table with a sample budget for the user."]
```
