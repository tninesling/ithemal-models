# Models

As part of the 2025 ithemal update, we have updated the codebase to Python 3 and a more recent version of PyTorch. This necessitated reproducing the existing RNN models, which are available for the following microarchitectures:

- Haswell (`hsw.dump` and `hsw.mdl`)
- Ivy Bridge (`ivb.dump` and `ivb.mdl`)
- Skylake (`skl.dump` and `skl.mdl`)

In addition to the RNN models, we include new Transformer-based models for the same microarchitectures:

- Haswell (`hsw_tsf.dump` and `hsw_tsf.mdl`)
- Ivy Bridge (`ivb_tsf.dump` and `ivb_tsf.mdl`)
- Skylake (`skl_tsf.dump` and `skl_tsf.mdl`)