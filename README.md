# Default Service
Put these files in your project, modify stater.sh and .service files, and run service_regi.sh, and your program will run in the background as a service.
> Set up the files below according to the instructions.

## stater.sh
Change SERVICE_NAME to your service name. Modify the Start Script below accordingly.

## service_name.service
Change service_name in the file name to your service name. Modify the internal items accordingly. Make ExecStart point to stater.sh.

## service_regi.sh
Set the internal variable SERVICE_NAME to the file name of service_name.service.

<hr>
<br>
Once you've set up everything, run sudo bash service_regi.sh. Is it registered properly?