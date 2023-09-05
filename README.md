# Codespace Demo

## Instructions

- Fork this repo
- Open as a codespace on GitHub at https://github.com/codespaces (or see next step)
- Or, open locally in VSCode and open a terminal once containers have been created.

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
