# git-github-behavior-samples
Github上におけるGitやGithubが容易する、ブランチのマージなどの挙動に関する例示を行うリポジトリ

# 例示した挙動の一覧

## PR "merge"
- 挙動: TrunkにはPRをMergeしたcommitのみ残る
- 用途: MergeされるPRが多くなるとき、commit logの可読性向上に資する
- PR: 子barnchをtrunkにMergeさせるPR #1

Squash and merge を未使用: 通常のMergeを行う #3
PR: 通常のMergeを行う #3
ChangeLog: 0.0.2...0.0.3


## PR "Squash and merge"

Issue: https://github.com/jun-g-0/git-github-behavior-samples/issues/2
- 挙動: TrunkにはPRをMergeしたcommitのみ残る
- 用途: MergeされるPRが多くなるとき、commit logの可読性向上に資する
- PR: 子barnchをtrunkにMergeさせるPR #1
- ChangeLog: 0.0.1...0.0.2

## PR "Rebase and merge"

Issue: https://github.com/jun-g-0/git-github-behavior-samples/issues/4


