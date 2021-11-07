# Schemat eksperymentów

Proponujemy schemat eksperymentów z wykorzystaniem:
- paczki Pytorch Lightning - do porządkowania kodu Pytorch-a 
- Hydra - do porządkowania configów
- WandB - do logowania

Przykład użycia znajduje się w [notatniku](notebooks/example_task.ipynb). Szczegółowy opis schematu [tutaj](docs/experiments_pipeline.md).

## Gotowe środowisko na kulfonie

Na kulfonie jest postawione środowisko `dl_template` (`/opt/tljh/user/envs/dl_template`), aktywacja przez:

```
source /opt/tljh/user/bin/activate
conda activate dl_template
```

W środowisku są zainstalowane wszystkie potrzebne paczki; jest ono także dostępne z poziomu *JupyterHub*. Są też ustawione zmienne środowiskowe `WANDB_API_KEY` oraz `WANDB_BASE_URL`, dzięki którym działa logowanie do lokalnej instancji wandb. Wyniki logowania można podejrzeć na `localhost:8081` po [zalogowaniu jako user portal](https://docs.google.com/document/d/1bxBiioSs0-n6ZHsaj25bcqrfqhSryWKK8euC9o9J64U/edit#heading=h.fvj32gx22jgq). Wyniki są zebrane w projekcie `dl_template_example`.


# Pozostałe

- [Setup środowiska dla nowego projektu](docs/setup_env.md)
- [Logowanie wyników](docs/logging.md)
- [Notebooks](docs/notebooks.md)
- [Przydatne uprawnienia do repozytorium](docs/set_permissions.md)
- [Git hooks](docs/git_hooks.md) - jakie git hooki warto mieć
- [Code style](docs/code_style.md) - czyli sugerowane typowanie, lintowanie
- [SSH](https://docs.google.com/document/d/1bxBiioSs0-n6ZHsaj25bcqrfqhSryWKK8euC9o9J64U/edit#heading=h.5w357sypyx69)

