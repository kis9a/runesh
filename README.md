# runeflex

## Install

```
go install github.com/kis9a/runewidth@latest
export RUNESH_INSTALL_PATH=/usr/local/bin/
curl --tlsv1.2 -sSf https://raw.githubusercontent.com/kis9a/runesh/main/install | sh
```

## Usage

<image width="680px" src="https://raw.githubusercontent.com/kis9a/runesh/main/runesh.png"></image>

### vim

#### runeboxes

```
:'<,'>!cat - | runeboxes
```

#### runeflexrn

```
:'<,'>!runeflexrn -mx 4 -py 2 -b ab
```
