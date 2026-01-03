# Cross Platform Starter

## Requirements

You need to have Leptos (nightly) and Tauri on your machine.
If not already, you can refer to [PREREQUISITES.md](PREREQUISITES.md).

## Run the project

```bash
pnpm i

# For Web
cargo leptos watch

# For desktop
cargo tauri dev

# For iOS
cargo tauri ios init
./run_ios.sh

# For Android
cargo tauri android init
./run_android.sh
```

## License

MIT License - see [LICENSE](LICENSE) for details.
