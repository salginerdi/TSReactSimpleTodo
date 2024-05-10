# TypeScript ve React ile Basit Todo List

Bu proje, TypeScript ve React kullanılarak oluşturulmuş basit bir Todo List uygulamasını içerir. Uygulama, kullanıcının yapılacak işleri ve bu işlerin yapılma süresini eklemesine ve silebilmesine olanak tanır.

incelemek için: [tıklayınız](https://tstodolist-woad.vercel.app/)

## Nasıl Çalıştırılır

1. Projeyi bilgisayarınıza klonlayın:
   git clone https://github.com/salginerdi/TSReactSimpleTodo.git
   
2. Proje dizinine gidin: proje aynı dizinde çalıştığı için . koyarak dizinde kalabilirsiniz.
   
3. Gerekli bağımlılıkları yükleyin: npm install
4. Uygulamayı başlatın: npm run dev 
5. Tarayıcınızda `http://localhost:5173` adresine gidin.

## Kullanım

- **Yeni bir görev eklemek** için "Yeni Görev Ekle" butonuna tıklayın.
- **Bir görevi silmek** için, görev altındaki "Sil" butonuna tıklayın.
___
# Simple Todo List with TypeScript and React

This project contains a simple Todo List application built with TypeScript and React. The application allows users to add and delete tasks, as well as specify their completion time.

to preview: [click here](https://tstodolist-woad.vercel.app/)

## How to Run

1. Clone the project to your computer:
   git clone https://github.com/salginerdi/TSReactSimpleTodo.git
   
2. Navigate to the project directory:
   Since the project runs in the same directory, you can stay in the directory by using a dot.
   
3. Install the necessary dependencies: npm install
4. Start the application: npm run dev 
5. Open your browser and go to `http://localhost:5173`.

## Usage

- To **add a new task**, click on the "Add New Task" button.
- To **delete a task**, click on the "Delete" button under the task.

___

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
