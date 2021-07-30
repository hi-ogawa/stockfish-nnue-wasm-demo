# stockfish-nnue.wasm demo

Demo frontend for [stockfish-nnue.wasm](https://github.com/hi-ogawa/Stockfish)

## Development

```
npm install

# Or use a local version of stockfish-nnue.wasm
npm install <path-to-repo-stockfish-nnue.wasm>/src/emscripten/public

# Link node_modules/stockfish-nnue.wasm to public/lib
npm run link-lib

npm run serve
```

## Deployment

```
# Copy node_modules/stockfish-nnue.wasm to public/lib
npm run copy-lib

# Run vercel cli
npm run deploy
```
