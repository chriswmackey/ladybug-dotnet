# This repository is no longer being developed

Any code that might have gone to this repository should now go to [ladybug-rhino](https://github.com/ladybug-tools/ladybug-rhino).

## ladybug-dotnet

A library for communicating between Ladybug Tools core Python libraries and .NET libraries

## Installation
```
pip install ladybug-dotnet
```

## QuickStart
```python
import ladybug_dotnet

```

## [API Documentation](http://ladybug-tools.github.io/ladybug-dotnet/docs)

## Local Development
1. Clone this repo locally
```
git clone git@github.com:ladybug-tools/ladybug-dotnet

# or

git clone https://github.com/ladybug-tools/ladybug-dotnet
```
2. Install dependencies:
```
cd ladybug-dotnet
pip install -r dev-requirements.txt
pip install -r requirements.txt
pip install pythonnet
```

3. Generate Documentation:
```
sphinx-apidoc -f -e -d 4 -o ./docs ./ladybug_dotnet
sphinx-build -b html ./docs ./docs/_build/docs
```
