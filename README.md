# Klaytn NFT BApp
Youtube Thumbnail NFT Market BApp 

<br />

## ⚙️ Version
- node 버전: 16.13.0
- npm 버전: 8.1.0
- truffle 버전: 5.1.23
- solidity 버전: 0.5.16

<br />

## 🎉 Get Started
#### 1-1. 프로젝트 root에 `config.js` 파일 생성 후 private key 입력
```js
export const PRIVATE_KEY = "" // Klaytn Wallet private key 입력
```
#### 1-2. `truffle-config.js` 파일 내 private key 입력
```js
const PRIVATE_KEY = ""; //Klaytn Wallet private key 입력
```
#### 2. NODE 모듈 설치
```
npm install
```
#### 3. Smart Contract Build
- ganache 에서 실행할 경우
```
truffle migrate --compile-all --reset --network ganache
```
- klaytn baobab 에서 실행할 경우
```
truffle migrate --compile-all --reset --network klaytn
```
#### 4. App 실행
```
npm run dev
```

<br />

##### 🔗 [인프런 강좌 URL](https://www.inflearn.com/course/%ED%81%B4%EB%A0%88%EC%9D%B4%ED%8A%BC-%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EC%96%B4%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98-erc721/dashboard)