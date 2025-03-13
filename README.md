# project-9-token-lottery

Token Lottery.

## Refer

- https://github.com/solana-developers/developer-bootcamp-2024/tree/main/project-9-token-lottery (code)
- https://www.youtube.com/watch?v=amAq-WHAFs8&t=30677s (video)

## Resources

- [Switchboard Documentation](https://docs.switchboard.xyz/docs/switchboard/switchboard-randomness)
- [Switchboard SDK](https://github.com/switchboard-xyz/sb-on-demand-examples/tree/main/sb-randomness-on-demand)

## How to run

- in `token-lottery.ts`
  - update `apiKey` to your helius api key.
  - update `queue_addr` to `A43DyUGA7s8eXPxqEjJY6EBu1KKbNgfxF8h17VAHn13w` if not yet.
- `cd setup`, then run:
  - `setup-local.sh` to export account & program to file.
  - `start-validator.sh` to start local validator, with account & program imported.
- run test, in localnet.
- each time run test, need to restart the validator first, due to account exists.

## Logic

- Create lottery as NFT.
- Buy lottery
- Open lottery, with randomness via switchboard.

## TODO
- test fail with error
