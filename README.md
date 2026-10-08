# MLOPS
ID: 99618

## Ćwiczenie 2

| Narzędzie | Czas instalacji | Plik zależności | Odtworzenie środowiska | Wykorzystanie |
|---|---:|---|---|---|
| venv | ~60 s | `requirements.txt` | `python -m venv .venv && pip install -r requirements.txt` | małe projekty |
| uv | ~31 s | `pyproject.toml` / `uv.lock` | `uv sync` | szybkie zarządzanie wieloma zależnościami |
| conda | ~1-10 min | `environment.yml` | `conda env create -f environment.yml` | projekty o wysokim zaawansowaniu wieloma procesami z bibliotekami, zarządzaniem GPU, czy zależnościami |

## DVC i wersjonowanie danych
**DVC**: zbiory danych, dane i modele ML
**GIT**: kod źródłowy, a repozytorium przechowuje metadane dla DVC
