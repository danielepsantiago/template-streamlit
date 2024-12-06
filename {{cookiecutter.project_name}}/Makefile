deploy:
	gcloud app deploy

permission:
    gcloud iap web add-iam-policy-binding \
    --resource-type=app-engine\
    --service={{cookiecutter.project_name}} \
    --member="group:todos@contaazul.com" \
    --role="roles/iap.httpsResourceAccessor"
