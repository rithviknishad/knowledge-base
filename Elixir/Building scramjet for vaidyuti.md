#### 1. Create a new Elixir project
```bash
mkdir scramjet
cd scramjet
git init
mix new .
```

#### 2. Add Dependencies
```bash
{:emqtt, github: "emqx/emqtt", tag: "1.6.1", system_env: [{"BUILD_WITHOUT_QUIC", "1"}]}
```
*Refferred from https://www.emqx.com/en/blog/mqtt-for-elixir*

#### 3. Update deps
```bash
mix deps.update --all
```

