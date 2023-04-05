## About

@ngx-tc/form-label is an Angular library that provides a UI component for displaying label text about form fields. This library allows developers to easily add field label to their forms, improving usability and accessibility for end-users. It is built on Angular and is designed to be lightweight, easy to use, and highly customizable.

## Usage

Install `@ngx-tc/form-label` in your project:

```
npm install @ngx-tc/form-label
```

Import `TcFormLabelModule` e.g. in your `app.module.ts`:
```typescript
import { TcFormLabelModule } from '@ngx-tc/form-label';

@NgModule({
  imports: [
    ...
    TcFormLabelModule
  ],
})
export class AppModule {}
```

Use the `tc-form-label` component in you app:
```html
<tc-form-label>
  Form control label
</tc-form-label>
```

## Demo
To view a working demo of the library in action, please follow the provided link. The demo will allow you to explore the various components and features included in this library and see how they can be used in your Angular applications.
[http://tc-library.type-code.pro/#/components/inputs](http://tc-library.type-code.pro/#/components/inputs)
