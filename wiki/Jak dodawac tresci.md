---
title: Jak dodawać treści
description: Krótka instrukcja redakcyjna i techniczna.
---

# Jak dodawać treści

Każdy publiczny artykuł jest zwykłym plikiem Markdown w katalogu `wiki/`. Kiln buduje z tych plików stronę oraz nawigację.

## Minimalny format artykułu

```markdown
---
title: Tytuł widoczny na stronie
description: Jednozdaniowy opis artykułu.
---

# Tytuł widoczny na stronie

Treść artykułu.
```

## Zasady robocze

- używaj krótkich, jednoznacznych nazw plików bez polskich znaków;
- łącz artykuły wewnętrznymi odsyłaczami w składni wikilinków Obsidiana;
- grafikę przechowuj w podkatalogu powiązanym z artykułem i dodawaj tylko wtedy, gdy wolno ją publicznie udostępnić;
- przed połączeniem zmiany uruchom kontrolę Kiln i obejrzyj wersję lokalną;
- nowe partie poradników dodawaj przez osobne pull requesty, aby treść i nawigację można było ocenić razem.

Wróć do [[index|strony głównej]].
