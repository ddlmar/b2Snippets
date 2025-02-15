<p align="center">
  <h3 align="center">B2 Snippets</h3>
</p>

## Content Table

- [Content Table](#content-table)
- [About this project](#about-this-project)
- [Install extension](#install-extension)
  - [Supported languages](#supported-languages)
- [Snippets](#snippets)
    - [React snippets](#react-snippets)
    - [React native snippets](#react-native-snippets)
    - [Styled component snippets](#styled-component-snippets)
    - [B2bit snippets](#b2bit-snippets)
- [Release Notes](#release-notes)
  - [1.0.0](#100)
  - [1.0.1](#101)
  - [1.0.2](#102)
  - [1.0.3](#103)
  - [2.0.0](#200)
  - [3.0.0](#300)

## About this project

This project aims to bring productivity to developers, specifically those from b2 company, bringing a set of snippets for web and mobile development

## Install extension

To install an extension you can run the **Command Pallete** using the command `Ctrl + Shift + P` or `Cmd + Shift + P` , type `Install Extensions` and press `Enter`, Once done, search for b2 snippets and you will find the extension **B2 snippets**.

### Supported languages

- TypeScript (.ts)
- TypeScript React (.tsx)

## Snippets

#### React snippets

| Command | Content                            |
| ------- | ---------------------------------- |
| `usst`  | Create functional useState hook    |
| `uscb`  | Create functional useCallback hook |
| `usef`  | Create functional useEffect hook   |
| `usmm`  | Create functional useMemo hook     |
| `crc`   | Create functional React component  |

#### React native snippets

| Command | Content                                  |
| ------- | ---------------------------------------- |
| `rncrc` | Create functional React native component |

#### Styled component snippets

| Command    | Content                                         |
| ---------- | ----------------------------------------------- |
| `rstyled`  | Create functional styled component              |
| `rnstyled` | Create functional React native styled component |

#### B2bit snippets

| Command            | Content                                           |
| ------------------ | ------------------------------------------------- |
| `b2context`        | Create React functional component with useContext |
| `b2hook`           | Create custom hook with request                   |
| `b2fnhook`         | Create custom minimal hook function               |
| `b2form`           | Create functional form                            |
| `b2controller`     | Create functional controller                      |
| `b2formController` | Create functional form with controller            |

## Release Notes

Update notes

### 1.0.0

created b2 snippets extension

### 1.0.1

changed [React snippets](#react-snippets) commands and fix `rncrc` command to return element

### 1.0.2

Update [B2bit snippets](#b2bit-snippets), changing b2form command

### 1.0.3

Fix [B2bit snippets](#b2bit-snippets), fixed generic type name and ForwardRefRenderFunction types.

### 2.0.0

Update [B2bit snippets](#b2bit-snippets), changed b2form, adding useFormik hook

Create [B2bit snippets](#b2bit-snippets), added a new command to create form with controller

### 3.0.0

Fix [B2bit snippets](#b2bit-snippets), changed b2form, b2formcontroller and b2hook

Create new [B2bit snippets](#b2bit-snippets) command, added b2fnhook
