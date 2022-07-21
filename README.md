This repository is used to test and demonstrate symlink errors with Ansible Controller.

To replicate the error, add this git repository as a new project in Controller, and wait for the initial sync to complete. It should be successful. A relaunch of this project sync should now cause a failure.

error: unable to create symlink test/myfile.txt: File exists

Even when adding Clean and Delete options on the project, there does not seem to be any change to the outcome.
