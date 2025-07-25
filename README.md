# Dora-OpenAI-Realtime (ROOT Repo)

## Front End

### Build Client

```bash
git clone https://github.com/haixuantao/makepad-realtime
cd makepad-realtime
cargo build --release
```

### Run Client

```bash
cd makepad-realtime
cargo run -r
```

## Server

### Build server

```bash
git clone https://github.com/haixuanTao/fastwebsockets
cd fastwebsockets/examples
uv venv --seed -p 3.11
dora build moyoyo-funasr-template-metal.yml --uv ## very long process

```

### Run server

```bash
cd fastwebsockets/examples
source .venv/bin/activate
dora up
cargo run --release --example echo_server --features upgrade

```

## On finish

```bash
dora destroy
```

## GUI

### Connect Client and Server ( English Version )

- Click on Connect to Finetuned Whisper
- When the session is ready
- Click on Start Conversation
- Start talking
- When finished click on Stop Conversation

### For chinese realtime server version

- Click on Connect to FunASR ( not working superwell for now )
- When the session is ready
- Click on Start Conversation
- Start talking
- When finished click on Stop Conversation

## Video tutorial
