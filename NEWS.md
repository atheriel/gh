# devel

-  Raw reponses from GitHub are returned as raw vector
-  Responses may be wrtten to disk by providing a path in the `destfile`
   argument
-  gh now sets `.Last.error` to the error object after an uncaught error,
   and `.Last.error.trace` to the stack trace of the error.
-  `gh()` now silently drops named `NULL` parameters, and throws an
   error for named `NA` parameters (#21, #84).
-  `gh()` now returns better values for empty responses, typically empty
   lists or dictionaries (#66).
-  `gh()` now has an `.accept` argument to make it easier to set the
   `Accept` HTTP header (#91).
-  New `gh_gql()` function to make it easier to work with the GitHub
   GraphQL API.

# 1.0.1

First public release.