<template>
    <header class="header">
        <div class="column right">
            <a target="_blank" href="https://virgool.io/@Ali_Z" class="item">
                <img src="../static/pictures/virgool.png" alt="virgool" />
            </a>
            <a target="_blank" href="https://github.com/Azeiynali" class="item">
                <img src="https://github.com/fluidicon.png" alt="github" />
            </a>
            <a target="_blank" href="https://huggingface.co/Ali-z" class="item">
                <img
                    src="../static/pictures/huggingface.svg"
                    alt="huggingface"
                />
            </a>
            <a target="_blank" href="https://medium.com/@azeiynali" class="item">
                <img
                    src="../static/pictures/medium.png"
                    alt="medium"
                />
            </a>
            <a target="_blank" href="https://codepen.io/Ali-zi" class="item">
                <img
                    src="https://cpwebassets.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico"
                    alt="codepen"
                />
            </a>
        </div>
        <div class="column left">
            <a target="_blank" href="mailto:Azeiynali@gmail.com" class="item">
                <img src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/gmail.ico" alt="gmail" />
            </a>
            <a target="_blank" href="mailto:Ali_Z_I@outlook.com" class="item">
                <img src="https://res-h3.public.cdn.office.net/owamail/20231013005.23/resources/images/favicons/mail-seen.ico" alt="outlook" />
            </a>
            <a target="_blank" href="https://www.chess.com/member/ali_z_i" class="item">
                <img src="https://www.chess.com/bundles/web/favicons/favicon-32x32.adae7142.png" alt="chess" />
            </a>
            <a target="_blank" href="https://www.linkedin.com/in/ali-z-346b02291/" class="item">
                <img src="https://static.licdn.com/aero-v1/sc/h/8s162nmbcnfkg7a0k8nq9wwqo" alt="chess" />
            </a>
            <a target="_blank" href="https://eitaa.com/AZeiynali" class="item">
                <img src="https://web.eitaa.com/assets/img/apple-touch-icon.png?v=jw3mK7G9Ry" alt="chess" />
            </a>
        </div>
        <img src="../static/pictures/me.png" alt="me" class="me" />
        <h1>Ali Zeiynali</h1>
        <small>Iran, qom</small>
    </header>
</template>

<script>
export default {
    name: "siteHeader",
};
</script>

<style scoped>
header.header {
    text-align: center;
    width: 80%;
    min-height: 100px;
    border-radius: 10px;
    background-color: var(--dark);
    padding: 20px;
    position: relative;
}
.right {
    position: absolute;
    top: 20px;
    right: 23px;
}
.left {
    position: absolute;
    top: 20px;
    left: 23px;
}
.column .item {
    margin-bottom: 10px;
    display: inline-block;
    width: 50px;
    height: 50px;
    background-color: white;
    border-radius: 5px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s;
    cursor: pointer;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.342);
}
.column .item:hover {
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.651);
    transform: scale(0.92);
}
.column .item img {
    width: 40px;
}
.me {
    width: 200px;
    border-radius: 10px;
}
</style>
