<header>
    <div class="wrapper">
    <div class="content">
        <h1><a class="zero" href="/">chrisch</a></h1>
        <h2><a class="zero" href="/projects">projects</a> - <a class="zero" href="/posts">posts</a></h2>
    </div>
    </div>
</header>

<style>
    header h1 {
        margin-top: 10px;
        margin-bottom: 10px;
    }
    header {
        position: fixed;
        width: 100vw;
        background-color: var(--headerColor);
        backdrop-filter: saturate(180%) blur(20px);
        -webkit-backdrop-filter: saturate(180%) blur(20px);
        text-align: center;
    }
    @-moz-document url-prefix() {
        header {
            background-color: var(--ffHeaderColor);
        }
    }
    .wrapper {
        width: 60vw;
        margin: 0 auto;
        border-bottom: 2px solid var(--borderColor);
    }
    .content {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    @media only screen and (max-width: 600px) {
        .wrapper {
            width: 85vw;
        }
    }
    header h2 {
        font-size: min(1.5em, 6vw);
    }
</style>