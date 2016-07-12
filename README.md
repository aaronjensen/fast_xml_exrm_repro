# FastXmlExrmRepro

https://github.com/processone/fast_xml/issues/10

## Repro

```bash
MIX_ENV=prod mix do deps.get, compile, release
ls rel/fast_xml_exrm_repro/lib
```

### Expected

`p1_utils` should be included in lib

### Actual

`p1_utils` is not included in lib
