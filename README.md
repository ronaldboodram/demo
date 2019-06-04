### Good reads:
1. Difference between the "images" fields in Cloudbuild and using Docker push comes down to seeing details about the images that were built by Cloudbuild in the logs. "https://cloud.google.com/cloud-build/docs/configuring-builds/store-images-artifacts"

2. Knative traffic splitting: https://github.com/meteatamel/knative-tutorial/blob/master/docs/04-trafficsplitting.md

3. Medium hands-on Knative series:
    * https://medium.com/google-cloud/hands-on-knative-part-1-f2d5ce89944e
    * https://medium.com/google-cloud/hands-on-knative-part-2-a27729f4d756
    * https://medium.com/google-cloud/hands-on-knative-part-3-d8731ad2f23d


4. Github Knative site: https://github.com/knative

5. Youtube video offering a good short overview of Knative: https://www.youtube.com/watch?v=Xi9oYTR710E&t=35s

6. Git cmds to remember:
    * Create a new branch:
    * >git checkout -b knative
    * Edit, add and commit your files.
    * Push your branch to the remote repository:
    * >git push -u google knative

7. Create service accounts for pulling code from Google Source Repositories 

8. Install custom builders and build templates before using them.

9. Ensure correct /workspace/folder-name/Dockerfile" is used.

10. How to install community builders: https://github.com/googlecloudplatform/cloud-builders-community
