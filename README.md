# 行きたい場所（サウナ訪問チェック）

静的フロントのみ。訪問状態は制限付き Edge Function `sauna-visits-personal-api` 経由で更新します。

開き方: `https://<pages-host>/#key=YOUR_CAPABILITY`

クライアントに Supabase プロジェクトキーは含みません。URL の `#key=` は公開URLに載るため誰でも見えます。プロキシは `sauna_visits` の visited 更新に限定されています。
