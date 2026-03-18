# DeepSpeech Eval Template

```python
import pandas as pd
from jiwer import wer

def evaluate(reference_path, hypothesis_path):
    refs = Path(reference_path).read_text().splitlines()
    hyps = Path(hypothesis_path).read_text().splitlines()
    return wer(refs, hyps)
```

- [ ] Add diarization-aware scoring
- [ ] Aggregate by speaker + noise label