# Weave Scope

Using Weave Scope with Kubernetes:
https://github.com/weaveworks/scope#using-weave-scope-with-kubernetes

If you have a scope.weave.works account and want to run Scope in Cloud Service Mode, comment out the line "$(WEAVE_SCOPE_APP_SERVICE_HOST):$(WEAVE_SCOPE_APP_SERVICE_PORT)"] 
in scope-probe-ds.yaml manifest and
uncomment the line below, replacing "foo" with the Service token which you will obtain when logging in to your 
scope.weave.works account:

"--probe.token=foo" ]
