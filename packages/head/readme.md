![React Email button cover](https://assets.react.email/covers/head.png)

<div align="center"><strong>@react-email/head</strong></div>
<div align="center">Contains head components, related to the document such as style and meta elements.</div>
<br />
<div align="center">
<a href="https://react.email">Website</a> 
<span> · </span>
<a href="https://github.com/zenorocha/react-email">GitHub</a> 
<span> · </span>
<a href="https://react.email/discord">Discord</a>
</div>

## Install

Install component from your command line.

#### With yarn

```sh
yarn add @react-email/head -E
```

#### With npm

```sh
npm install @react-email/head -E
```

## Getting started

Add the component to your email template. Include children tags where needed.

```jsx
import { Head } from '@react-email/head';

const Email = () => {
  return (
    <Head>
      <title>My email title</title>
    </Head>
  );
};
```

## Support

This component was tested using the most popular email clients.

| <img src="https://assets.react.email/icons/gmail.svg" width="48px" height="48px" alt="Gmail logo"> | <img src="https://assets.react.email/icons/apple-mail.svg" width="48px" height="48px" alt="Apple Mail"> | <img src="https://assets.react.email/icons/outlook.svg" width="48px" height="48px" alt="Outlook logo"> | <img src="https://assets.react.email/icons/yahoo-mail.svg" width="48px" height="48px" alt="Yahoo! Mail logo"> | <img src="https://assets.react.email/icons/hey.svg" width="48px" height="48px" alt="HEY logo"> | <img src="https://assets.react.email/icons/superhuman.svg" width="48px" height="48px" alt="Superhuman logo"> |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Gmail ✔                                                                                            | Apple Mail ✔                                                                                            | Outlook ✔                                                                                              | Yahoo! Mail ✔                                                                                                 | HEY ✔                                                                                          | Superhuman ✔                                                                                                 |

## License

MIT License
