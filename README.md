Get-ChildItem -Path . -Filter __pycache__ -Recurse | ForEach-Object { git rm -r --cached $_.FullName }
dict(self.env['model']._fields[field].selection)
