<!-- BEGIN shared-rules (auto) -->
# 共通ルール（AI組織・自動同期・手で編集しないでください）

このブロックは `ai-ops-config` リポジトリの `SHARED_RULES.md`（正典）から自動生成されています。
**ルールを追加・変更したい場合はこのファイルではなく、正典
`https://github.com/yusuken10121990-hub/ai-ops-config/blob/main/SHARED_RULES.md` を編集してください。**
PC・クラウド(スマホ含む)どちらの環境から編集してもOKです。次回の自動同期(毎日)で全リポジトリに
反映されます。

## 最重要ルール（要約）
- YESが必要なのは「お金が実際に動く操作」（広告費/入札変更・新規出稿・決済・新規有料契約）だけ。
  それ以外は確認せず自動で進める。
- 実質的な検討・実装は CEO/CTO/CMO/Engineer 等の専門エージェントに委任する。
- 「ダッシュボード更新して」と言われても、ソースリポジトリを探さない/手で編集しない/オーナーに場所を
  聞かない。台帳を更新し `gh workflow run dashboard-sync.yml -R yusuken10121990-hub/ai-ops-orchestrator`
  を叩けば自動反映される。
- LINE通知は金銭承認依頼のみ。
- 秘密情報はコードに直書きしない。

完全な全条文は正典 `ai-ops-config/SHARED_RULES.md` を参照。
<!-- END shared-rules (auto) -->
