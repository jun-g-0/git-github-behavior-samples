# git-github-behavior-samples
Github上におけるGitやGithubが容易する、ブランチのマージなどの挙動に関する例示を行うリポジトリ

# 例示した挙動の一覧

## "Squash and merge" #1
仮説:
- 使用時: TrunkにはPRをMergeしたcommitのみ残る
- 未使用時: 子branchのcommitが残る上、Merge commitも追加される
その他: MergeされるPRが多くなるとき、commit logの可読性向上に資する
