# Exercice Bootstrap 1 - Layout Desktop

Intégrez les 2 maquettes en utilisant la grille Bootstrap.

### Trouver les maquettes

Le fichier se trouve:

- dans l'équipe de votre classe
- dans le projet _FD-03-Bootstrap_

Il se nomme _01 - Bootstrap - Layout desktop_.

Vous pouvez également le trouver [ici](https://www.figma.com/file/GwaHaRS7UeCKrU7g0ytx12/01---Bootstrap---Layout-desktop?type=design&mode=design&t=YfCKLUgi2SujFDQV-1).

### Rendre les colonnes visibles

Afin de rendre les colonnes visibles, vous pouvez utiliser la CSS suivante:

```CSS
.row + .row {
  margin-top: 16px;
}

.row > .col,
.row > [class^=col-] {
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: rgba(86, 61, 124, .15);
  border: 1px solid rgba(86, 61, 124, .2);
}
```

![](_screenshots/maquette1@1x.png)
![](_screenshots/maquette2@1x.png)
