# json2jsonl

Converts input file from `json` format
```json
[
  {"foo":  "bar"},
  {"bar":  "buz"}
]
```

to `jsonl` format
```json
{"foo": "bar"}
{"bar": "buz"}
```

## Usage

```bash
$ ./json2jsonl.py input_file.json output_file.jsonl
```
