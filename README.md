# Oh My Zsh plugin for Elixir, IEx, Mix, Kiex and Phoenix

Terminal shortcuts for Elixir developers.

## Install and run
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/gusaiani/elixir-oh-my-zsh.git elixir
```

Enable it by adding _elixir_ to the [_plugins array_](https://github.com/robbyrussell/oh-my-zsh/blob/master/templates/zshrc.zsh-template#L54).
You have to restart your current terminal in order to use the aliases below.
```
# located under $HOME/.zshrc
plugins=(git elixir)
```

## Functions

| Function                 | Command
| :------------------------| :--------------------------------
| mncd app-name            | mix new app-name; cd app-name

## Aliases

| Alias                    | Command
| :------------------------| :--------------------------------
| i                        | iex
| ips                      | iex -S mix phx.server
| ism                      | iex -S mix
| m                        | mix
| mab                      | mix archive.build
| mai                      | mix archive.install
| mat                      | mix app.tree
| mc                       | mix compile
| mcv                      | mix compile --verbose
| mcl                      | mix clean
| mdl                      | mix dialyzer
| mdlp                     | mix dialyzer --plt
| mcr                      | mix credo
| mcrs                     | mix credo --strict
| mcx                      | mix compile.xref
| mdc                      | mix deps.compile
| mdg                      | mix deps.get
| mdgc                     | mix do deps.get, deps.compile
| mdt                      | mix deps.tree
| mdu                      | mix deps.update
| mdua                     | mix deps.update --all
| mdun                     | mix deps.unlock
| mduu                     | mix deps.unlock --unused
| meb                      | mix escript.build
| mec                      | mix ecto.create
| mecm                     | mix do ecto.create, ecto.migrate
| med                      | mix ecto.drop
| mem                      | mix ecto.migrate
| megm                     | mix ecto.gen.migration
| merb                     | mix ecto.rollback
| mers                     | mix ecto.reset
| mes                      | mix ecto.setup
| mho                      | mix hex.outdated
| mlh                      | mix local.hex
| mn                       | mix new
| mns                      | mix new --sup
| mpgc                     | mix phx.gen.channel
| mpgh                     | mix phx.gen.html
| mpgj                     | mix phx.gen.json
| mpgm                     | mix phx.gen.model
| mpgs                     | mix phx.gen.secret
| mpn                      | mix phx.new
| mpr                      | mix phx.routes
| mps                      | mix phx.server
| mr                       | mix run
| mrnh                     | mix run --no-halt
| mrl                      | mix release
| mt                       | mix test
| mts                      | mix test --stale
| mtw                      | mix test.watch
| mx                       | mix xref
| hrmec                    | heroku run mix ecto.create
| hrmem                    | heroku run mix ecto.migrate
| kd                       | kiex default
| ki                       | kiex install
| kl                       | kiex list
| klb                      | kiex list branches
| klk                      | kiex list known
| klr                      | kiex list releases
| ks                       | kiex shell
| ksu                      | kiex selfupdate
| ku                       | kiex use
