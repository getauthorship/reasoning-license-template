# LICENSE_VARIANTS.md

## Overview: Herbert, Asimov, Heinlein Licenses

The Authorship Reasoning License (ARL) suite includes three license types for reasoning logic modules. These licenses apply to structured logic components (e.g., prompt templates, symbolic graphs, agent policies) that are separate from any foundation model weights, tokenizers, or training data.

---

## License Details

### Herbert License

A permissive license based on the terms used in the MIT License.  
- **Commercial Use:** Allowed  
- **Redistribution:** Allowed  
- **Attribution:** Required  
- **Patent Grant:** Not included  
- **Technical Separation Required:** Yes
  
Use this license for open access and flexible reuse across research and production settings.

### Asimov License

A patent-grant license based on the terms used in the Apache 2.0 License.  
- **Commercial Use:** Allowed  
- **Redistribution:** Allowed (same license)  
- **Attribution:** Required  
- **Patent Grant:** Included  
- **Technical Separation Required:** Yes
   
Use this license for logic intended for commercial integration where patent rights apply.

### Heinlein License

A restricted-use license based on the community research license terms used by Meta (i.e., for models like LLaMA).  
- **Commercial Use:** Not allowed  
- **Redistribution:** Not allowed (without written permission)  
- **Attribution:** Required  
- **Patent Grant:** Not included  
- **Technical Separation Required:** Yes
  
Use this license for academic research, evaluation, or internal development without commercial distribution.

---

| License   | Commercial Use | Redistribution                    | Patent Grant | Attribution | Based On          |
|-----------|----------------|------------------------------------|--------------|-------------|-------------------|
| Herbert   | Yes            | Yes                                | No           | Yes         | MIT               |
| Asimov    | Yes            | Yes (same license)                 | Yes          | Yes         | Apache 2.0        |
| Heinlein  | No             | No (without written permission)    | No           | Yes         | Meta Research     |

---

## Technical Separation Requirement

All licenses require reasoning logic to remain separate from the foundation model.

Accepted formats include:
- Prompt files (e.g., `.txt`, `.yaml`)
- Adapter checkpoints (e.g., LoRA, delta weights)
- Symbolic workflows (e.g., logic graphs or policy scripts)

These components must be stored and maintained separately from any model weights, embedding files, or code dependencies tied to specific deployment setups.

---

## Attribution Requirement

All public or production use must visibly include:

> “Reasoning powered by Authorship – https://authorship.com”

---

## Contact

For custom licensing, integration, or questions: 📧 legal@authorship.com
