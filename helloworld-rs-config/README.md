Prerequisites before deploying the application:
1.  Deploy the configmap located under /src/ocp directory
2.  Grant permission to the service account to consume the configmap by running:
    oc policy add-role-to-user view system:serviceaccount:{project}:default

    Replace {project} above with the project name where you are deploying the application
