# Exercice CSS : Sélecteurs avancés

## Consigne

Votre mission : **implémentez chacune des règles** ci-dessous **exactement** comme décrit. Chaque point utilise un sélecteur ou un ensemble de sélecteurs précis. **Respectez** l’ordre, et **n’inventez rien d’autre** : on veut simplement vérifier la bonne exécution technique.

### 1.1 Sélecteurs élémentaires et combinés

1. **Sélecteur de type** :

   - Tous les `<p>` du document doivent avoir une marge de `1em` et une couleur de texte `#333`.

2. **Sélecteur d’ID** :

   - L’élément `#presentation` doit avoir un fond légèrement gris (ex. `background-color: #f2f2f2`).

3. **Sélecteur de classe** :
   - Tous les éléments avec la classe `.special` doivent apparaître en **italique** et en **couleur #0099cc**.

### 1.2 Sélecteurs de descendance et enfant direct

4. **Sélecteur de descendance**

   - Ciblez tous les `<em>` à l’intérieur de `#presentation` pour les mettre en **gras** (`font-weight: bold;`).

5. **Sélecteur enfant direct (`>`)**
   - Sélectionnez **uniquement** les `<li>` qui sont enfants directs de `.list` et donnez-leur un `border: 1px solid red;` ainsi qu'une marge.

### 1.3 Sélecteurs d’adjacence (`+`) et de frères généraux (`~`)

6. **Sélecteur d’adjacence (`+`)**

   - Sélectionnez le `<p>` qui vient **juste après** un `<p class="special">` et mettez son texte en **majuscule** (`text-transform: uppercase;`).

7. **Sélecteur général de frères (`~`)**
   - Dans le `<aside>`, sélectionnez tous les `<li>` qui viennent **après** le `<li class="urgent">` et mettez leur texte en **italique**.

### 1.4 Pseudo-classes structurales

8. **`:first-of-type`**

   - Dans chaque `<article>`, le **premier** `<p>` doit avoir un **fond jaune** (`background: yellow;`).

9. **`:nth-child(n)`**

   - Dans chaque `<article>`, le **troisième** `<p>` doit avoir une **bordure verte** (`2px solid green;`).

10. **`:last-child`**
    - Dans la liste `<ul>` du `<aside>`, le **dernier** `<li>` doit s’afficher en **rouge**.

### 1.5 Autres sélecteurs utiles

11. 🏎️ **Sélecteur d’attribut**

    - Ajoutez un attribut `data-note="secret"` sur un `<p>` ou `<strong>` de votre choix dans le HTML.
    - Appliquez-lui un style spécial à l’aide du sélecteur `[data-note="secret"]` (ex. bordure en pointillés).

12. 🏎️ **Pseudo-classes d’état :hover**
    - Survolez (`:hover`) les `<li>` de la liste d’actualités : changer la couleur de fond en gris clair et le curseur en `pointer`.

**Amusez-vous bien !**
