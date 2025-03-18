<script>
    import logo from './asset/tulo-logo.png';
</script>
<div class='header'>
    <img id='tulo-icon' src={logo} alt='Tulo Logo'>
</div>
<style>
    .header {
        position: fixed;
        top: 0;
        left: 0;
        height: 100px;
        width: 100%;
        z-index: 99;
        background-color: #FEFBE9;
    }

    #tulo-icon {
        position: fixed;
        height: 80px;
        width: auto;
        top: 10px;
        left: 25px;
    }

    @media screen and (max-width: 1300px) {
        .header {
            height: 80px;
        }

        #tulo-icon {
            height: 60px;
        }
    }
</style>