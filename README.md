# lit_bashwork component

This ⚡ [Lightning component](lightning.ai) ⚡ was generated automatically with:

```bash
lightning init component lit_bashwork
```

## To run lit_bashwork

First, install lit_bashwork (warning: this app has not been officially approved on the lightning gallery):

```bash
lightning install component https://github.com/robert-s-lee/lit_bashwork
```

Once the app is installed, use it in an app:

```python
from lit_bashwork import TemplateComponent
import lightning_app as la


class LitApp(lapp.LightningFlow):
    def __init__(self) -> None:
        super().__init__()
        self.lit_bashwork = TemplateComponent()

    def run(self):
        print(
            "this is a simple Lightning app to verify your component is working as expected"
        )
        self.lit_bashwork.run()


app = lapp.LightningApp(LitApp())
```
