## Next Aggregate ERC20 Swap (Next.js)

![Modern Neon Sci-Fi Fantasy Book Cover  copy](https://github.com/FanbaseLabs/React-Aggregate-ERC20-Swap/assets/145924938/277ca724-0bf4-4815-a4f9-12a26d467a69)

A minimal Next.js integration example for `fanbase-aggregate-erc20-swap-widget` to enable ERC20 swaps across EVM networks.

![PM-3](https://github.com/FanbaseLabs/React-Aggregate-ERC20-Swap/assets/145924938/58fb1d00-438f-494d-9c18-53dbc6549c1d)

## Stack Used

- Next.js 13 (`pages` router)
- React 18
- `fanbase-aggregate-erc20-swap-widget` (loaded with dynamic import in `pages/index.tsx`)

## Quick Start

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Widget Configuration

Widget props are configured in `pages/index.tsx`:

- `appId` - application key from `plan.fanbase.io`
- `chainId` - target EVM chain ID

## Useful Links

- Plans and app keys: `https://www.plan.fanbase.io`
- Widget docs: `https://fanbase-io.gitbook.io/docs/reference/swap-widget-sdk/aggregate-swap-widget`
