# Modal Component

A customizable Modal component for React.

## Installation

You can install the package using npm:

```shell
npm install oc-modal-p14
```

Import the Counter component:

```js
import {Modal} from "oc-modal-p14/src/Modal/Modal.tsx";

```
### Modal Props

| Prop        | Type      | Description                                          |
|-------------|-----------|------------------------------------------------------|
| `text`      | `string`  | The message to display in the modal.                 |
| `showModal` | `boolean` | Controls the visibility of the modal.                |
| `error`     | `boolean` | Indicates if the modal should display an error style. |


### Usage

#### Exemple 1 : Modal with sucess style

```jsx
<Modal text="Employé créé avec succès !" showModal={true} error={false} />
```
#### Exemple 2 : Modal with error style

```jsx
<Modal text="Veuillez remplir tous les champs !" showModal={true} error={true} />
```

#### Exemple 2 : Modal with default style (remove error prop)

```jsx
<Modal text="Veuillez remplir tous les champs !" showModal={true} />
```
# oc-modal-p14
