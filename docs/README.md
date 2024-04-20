Use this template to set up your pdm project using:
```shell
pdm init https://github.com/eckelsjd/website.git
```

**THE REST OF THIS README** will be populated with your project information. PLEASE IGNORE. You can delete
this text in your own readme file. Note that you will also have to manually fill in all broken links with your own
information (such as Github repo links, PyPI package links, etc.)

## Installation
You can install normally with:
```shell
pip install website
```
If you are using [pdm](https://github.com/pdm-project/pdm) in your own project, then you can use:
```shell
cd <your-pdm-project>
pdm add website
```
You can also quickly set up a development environment with:
```shell
# After forking this project on Github...
git clone https://github.com/<your-username>/website.git
cd website
pdm install  # reads pdm.lock and sets up an identical venv
```

## Quickstart
```python
import website

website.do_something()

print('Wow!')
```

## Contributing
See the [contribution](CONTRIBUTING.md) guidelines.

## Citations
Include any additional references for your project.

<sup><sub>Made with the [UQ pdm template](https://github.com/eckelsjd/website.git).</sub></sup>

