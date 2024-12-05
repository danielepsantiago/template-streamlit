deploy:
	gcloud app deploy

permission:
	gcloud projects add-iam-policy-binding contaazul-ds-dev \
    --member="group:todos@contaazul.com" \
    --role="roles/iap.httpsResourceAccessor"
