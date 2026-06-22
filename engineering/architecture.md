# Architecture / Engineering

開発設計、RAGアーキテクチャ、セキュリティ、他社事例などのリンク集。

## Security（シークレットスキャン）

* [gitleaks](https://github.com/gitleaks/gitleaks) - Gitリポジトリ・ファイル・stdinからパスワード・APIキー・トークンなどのシークレットを検出するCLIツール（Go製）。正規表現＋エントロピーで検出し、pre-commitフックやGitHub Actionsに組み込める。TOMLでルール・allowlistをカスタマイズ可能。リポジトリへのシークレット混入防止の定番。 #security #secrets-scanning #cli
* [betterleaks](https://github.com/betterleaks/betterleaks) - Gitleaks開発陣（オリジナル作者含む）が手がけるシークレットスキャナの後継。CELベースの表現力の高いフィルタ（allowlist相当）、検出したシークレットの有効性をHTTPで非同期検証する機能、BPEトークン化による自然言語の誤検知抑制、GitHub/GitLab/S3など多様なソース対応が特徴。Gitleaksより高機能・低誤検知。 #security #secrets-scanning #cli
