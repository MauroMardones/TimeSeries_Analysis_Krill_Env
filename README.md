# TimeSeries_Analysis_Krill_Env
TS analysis for krill data environmental

Is a complenet to krill correlation analysis between environmental data and recritument krill  

To conenct local and remote repo

use this two step;

RStudio needs a personal access token for accessing GitHub. The following command will bring you to the GitHub webpage that creates that personal access token:

usethis::create_github_token()

You can edit the Note to something like “mizer course” or whatever will remind you later what this was for. You can leave the rest of the form as it is and scroll down to the bottom and press the “Generate token” button. That will lead you to a page that displays your new token:

Copy the token to your clipboard (using the button circled in the above screenshot). Switch to RStudio and issue the command

gitcreds::gitcreds_set()


