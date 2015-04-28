# Rails params parsing

# README

### Set me up

1. Fork, clone, bundle
1. rails s
1. Navigate to root path (http://localhost:3000/)

### Learn about creating params from forms

#### Some pre-questions

1. Where do params come from?
they come from the URL
they come from form fields
they come from queries
1. Where do params "go"?

1. What is the general format of params?
hashes
1. How do you find out exactly which params are coming into your app?
you can puts out params.

#### Simple params

1. Click submit. Currently the form is not passing params. How do we change this?
  * Inspect element on the input field
1. Check out another project's form (in production or running locally)
  * Inspect element on the input field. What was missing from the previous form?
1. Open the rails project in a text editor and change the input field to add the missing element.
  * ***ONLY make changes where indicated in each matching view***
  * Submit the form. If your params match the expected params, success! Commit and move to the next exercise.

#### Nested params

* Follow the same format as before. What project have you made where you used nested params? (Think `form_for [@thing, @other_thing] do...`)

#### Deeply nested params

* Extrapolate on the pattern in the previous example. Hint: How would you access that hash value?

#### Array

* As this involves checkbox, be sure to check out a previous project's checkbox (in production or running locally)
* This one is tricky. Play around with some ideas you might have, then check out the suggested resources.

#### Hash

* We have been creating hashes this whole time, but this one is a little special. Try a few things, and extrapolate a bit from the array exercise. Also check out the suggested resources if you are stuck.


### Suggested Resources:

* http://guides.rubyonrails.org/action_controller_overview.html#parameters
* http://guides.rubyonrails.org/form_helpers.html#understanding-parameter-naming-conventions
