SHELL := /bin/bash
include .env


authenticate-databricks:
	databricks auth login --host https://accounts.cloud.databricks.com --account-id ${DATABRICKS_ACCOUNT_ID}
