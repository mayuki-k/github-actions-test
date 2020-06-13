# github-actions-test

## GitHub Actionsとは

- [この記事わかりやすい](https://knowledge.sakura.ad.jp/23478/)

- とりあえず注意しなくてはいけないのは制限があること。

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

- 参考URL:https://qiita.com/szk3/items/38a3dba7fdfed189f4c9

