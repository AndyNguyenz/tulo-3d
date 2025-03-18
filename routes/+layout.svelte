<script>
	import Header from "../lib/Header.svelte";
    import '../style/index.css';
</script>

<header>
    <Header/>
</header>
<main>
    <!--Main content-->
    <slot></slot>
</main>

<style>
    header {
        display: flex;
    }

    main {
        height: calc(100% - 140px);
        position: absolute;
        margin: 0 auto;
        top: 120px;
        left: calc(5%);
        width: 90%;
        background-color: rgba(0, 0, 0, 0.6);
    }

    @media screen and (max-width: 1300px) {
        main {
            height: calc(100% -120px);
            top: 110px;
        }
    }
</style>