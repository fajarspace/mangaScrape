# Manga API
Restful API Manga bahasa Indonesia built with ❤️ and node.js

# Usage
1. Clone this repository
    ```bash
    git clone https://github.com/febryardiansyah/manga-api.git
    ```
2. Install dependecies (`yarn` or `npm install`)
3. Start the development environment (*if you haven't installed nodemon globally, you can do `npm i nodemon --save`)
    ```bash
    npm run dev or npm run start
    ```
4. visit http://localhost:3000/api

# Documentation
__API__ __PATH__ = https://weebkomik.up.railway.app/api/
</br>__ApI__ Version = `v2.0`

## All Manga
Get Latest Manga Update
```
/manga/page/[pagenumber]
```
example : https://weebkomik.up.railway.app/api/manga/page/1

## Popular Manga
Get Popular Manga
```
/manga/popular/[pageNumber]
```
example : https://weebkomik.up.railway.app/api/manga/popular/1

## Detail Manga
```
/manga/detail/[endpoint]
```
example : https://weebkomik.up.railway.app/api/manga/detail/after-transformation-mine-and-her-wild-fantasy/

## Search Manga by Name
```
/search/[query]
```
example : https://weebkomik.up.railway.app/api/search/komi%20san

## Genre List
```
/genres
```
example : https://weebkomik.up.railway.app/api/genres

## Genre Detail
```
/genres/[endpoint]/[pagenumber]
```
example : https://weebkomik.up.railway.app/api/genres/action/1

## Recommended Manga
```
/recommended
```
example : https://weebkomik.up.railway.app/api/recommended

## Manhua List (Chinese Comic)
```
/manhua/[pageNumber]
```
example : https://weebkomik.up.railway.app/api/manhua/1

## Manhwa List (Korean Comic)
```
/manhwa/[pageNumber]
```
example : https://weebkomik.up.railway.app/api/manhua/1

## Chapter
```
/chapter/[chapterEndpoint]
```
example :https://weebkomik.up.railway.app/api/chapter/after-transformation-mine-and-her-wild-fantasy-chapter-70-bahasa-indonesia/

## Showcase
App Showcase that use this API (you can add your app by edit this readme)

- [MangaMint](https://github.com/febryardiansyah/manga_mint) Flutter Manga Reader Application by [Febry ardiansyah](https://github.com/febryardiansyah)
