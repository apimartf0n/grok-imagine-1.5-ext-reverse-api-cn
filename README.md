# Grok Imagine 1.5 Ext — 逆向 route (简体中文)

> **1K $0.015** · model ID `grok-imagine-1.5-apimart` · **逆向/逆向工程** route.

**[查看实时价格](https://go.apimart.ai/k-0d02cc)** · **[领取 API Key](https://go.apimart.ai/k-6306b1)**

grok-imagine-1.5-ext-reverse-api-cn 是 **逆向** 的 Grok Imagine 1.5 Ext 接入仓库：调用 ID `grok-imagine-1.5-apimart`，与官方转接（`grok-imagine-image`）并行存在，单价更低。

## 价格 (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.015 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"grok-imagine-1.5-apimart","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **逆向** | `grok-imagine-1.5-apimart` | 1K $0.015 |
| 官方转接 | `grok-imagine-image` | official list price, billed at ×0.8 group ratio |


## Keywords

`grok-imagine-1.5-ext` · `grok-imagine-1.5-apimart` · `逆向` · `逆向工程` · `API 中转站` · `AI API 网关` · `统一接入` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

