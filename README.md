# github-actions-test
GitHubActionのテスト

# CloudRunデプロイ

## 権限

- iam.serviceaccounts.actAs
- https://cloud.google.com/compute/docs/access/iam?hl=ja#iam.serviceAccountUser

## 案1

- gcloudでCloudRunへのデプロイを頑張っている
- 権限はCloudRunとCloudStorage(GCRかな？)とCloudBuild
- CloudBuildAPIを有効にする？
- 有効にしたらstorage access denied。CloudBuildの権限も必要？ 

## 案2

