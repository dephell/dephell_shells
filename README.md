# Dephell Shells

Run shell for virtual environment.

## Installation

```bash
python3 -m pip install --user dephell_shells
```

## Usage

```python
from pathlib import Path
from dephell_shells import Shells

shells = Shells(bin_path=Path('/home/gram/.../dephell-nLn6/bin'))
shells.current
# ZshShell(bin_path=Path('/home/gram/.../dephell-nLn6'), shell_path=Path('/usr/bin/zsh'))
shells.current.run()
```
