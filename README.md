# React Toxic Editor 🙃

This is a high-quality, feature-rich React-based text editor that offers a seamless user experience. With the ability to add images, links, and more, See this [react-toxic-editor](https://github.com/chaudev/react-toxic-editor) is the perfect solution for anyone looking for a powerful and flexible text editor, this editor is an excellent choice for your next project.

### Install

```
yarn add react-toxic-editor
```

or

```
npm install react-toxic-editor
```

### Requirement \*

- [SASS](https://www.npmjs.com/package/sass)
- [React Tinymce](https://www.npmjs.com/package/@tinymce/tinymce-react)
- [Ant Design](https://ant.design/docs/react/getting-started)

Install the libraries in the "Requirement" section according to the documentation provided by the library. I will try to remove the requirements in the next versions.

### Example import

```tsx
import ToxicEditor from "react-toxic-editor";
```

### Example use:

```tsx
<ToxicEditor
  id="trash-item"
  height={160}
  initialValue="I want a raise"
  onChange={(text: string) => {
    // ... do something
  }}
/>
```

### About me:

[Nguyen Phuc Bao Chau](https://ischau.org/nguyen-phuc-bao-chau)
