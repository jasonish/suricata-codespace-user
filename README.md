# Suricata Codespace for Users

## Instructions

### Using GitHub Codespaces

- Fork this repo
- Open as a codespace on GitHub at https://github.com/codespaces (or see next step)

### Running Locally

- Clone this repo
- Open in Visual Studio Code
- When prompted, "Reopen in Container"

## Things to Try

### Run Suricata on a PCAP

```
suricata -r ./pcaps/eicar.com.pcap
```

### View Alert with JQ

```
jq -c 'select(.event_type == "alert")' ./eve.json
```

### Modify / Create a Rule

In VSCode (locally, or in the Codespace), open `rules/demo.rules` and start
creating a rule. The Suricata Language Server should help you along.
