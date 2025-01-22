#### stream-one
```bash
 ┌─────────┐      upload/download         ┌─────────┐        ┌─────────┐
 │  client ├◄────────────────────────────►┤   vps   ├◄──────►┤ website │
 └─────────┘                              └─────────┘        └─────────┘
```

#### other modes
```bash
┌─────────┐           upload              ┌─────────┐        ┌─────────┐
│  client ├──────────────────────────────►┤   vps   ├◄──────►┤ website │
└───────▲─┘                               └────┬────┘        └─────────┘
        │            download                  │
        └──────────────────────────────────────┘
```

#### with download settings
```bash
 ┌─────────┐            upload            ┌─────────┐        ┌─────────┐
 │  client ├─────────────────────────────►┤   vps   ├◄──────►┤ website │
 └───────▲─┘                              └────┬────┘        └─────────┘
         │                                     │
         │             download           ┌────▼────┐
         └────────────────────────────────┤   vps2  │
                                          └─────────┘
```