# sample_issue_component
AEM Link checker's closing brace image goes missing when we insert an image component between anchor tags.
AEM's link cheker functionaity marks the broken links on component / page and marks it with an image, a red colored opening brace image and a red colored closing image.
But I have found a bug in this link checker's functionlity .
When we insert an image component inside the <a> </a> ( anchor tags) The closing brace image of the linkchecker goes missing. Which means that closing brace is not displayed for the above case.
This is component that will expose this bug .
# startup_ui_site
