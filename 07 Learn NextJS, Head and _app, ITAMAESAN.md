We wuill use _app.js to put there the Head content to repeat in al, all pages.

_app.js Will look like:
    import Head from 'next/head'
    import '../styles/globals.css'

    function MyApp({ Component, pageProps }) {
    return <>

    <Head>
        <title>NewsApp</title>
        <meta name="description" content="News App by ITAMAESAN" />
        <link rel="icon" href="/favicon.ico" />
    </Head>

    <header>📰 newsapi</header>
    <Component {...pageProps} />
    </>
    }

    export default MyApp

And index.js will look like this:

    import Head from 'next/head'
    import styles from '../styles/Home.module.css'

    export default function Home() {
    return (
        <div className={styles.container}>
        <Head>
            <title>NewsApp - Home</title>
        </Head>

        <h1>Learning NextJS with ITAMAESAN</h1>
        </div>
    )
    }

In this way, if you forgot to put titles on the pages, you can use the Head component to put the title on the page on the _app.js
This will allow you to put the title on all pages and also individually.

 - <- [06 Learn NextJS, cd news-app, ITAMAESAN](https://github.com/itamaesanorg/How-To-NextJS/blob/main/06%20Learn%20NextJS%2C%20cd%20news-app%2C%20ITAMAESAN.md)
 - -> [08 Learn NextJS, components, ITAMAESAN](https://github.com/itamaesanorg/How-To-NextJS/blob/main/08%20Learn%20NextJS%2C%20components%2C%20ITAMAESAN.md)
