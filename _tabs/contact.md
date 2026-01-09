---
icon: fas fa-envelope
order: 3
---

<style>
    @media (min-width: 600px) {
        .mobile {
            display: none;
        }

        .name {
            border: 1px solid white;
            border-radius: 6px;
            width: 38%;
            margin-left: 38px;
        }

        .name placeholder {
            position: relative;
            left: 10px;
        }

        .mail {
            border: 1px solid white;
            border-radius: 6px;
            width: 38%;
            margin-right: 38px;
        }

        .msg {
            border: 1px solid white;
            border-radius: 6px;
        }

        .info {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

        .separator {
            border: 1px solid white;
            margin: 24px auto;
            width: 50%;
        }

        button {
            padding: 0.688rem 1.563rem;
            border: 0px;
            border-radius: 0.375rem;

            font-size: 0.938rem;
            letter-spacing: -1.5%;
            font-weight: 500;
        }
    }

    @media (max-width: 600px) {
        .desktop {
            display: none;
        }

        .name {
            border: 1px solid white;
            border-radius: 6px;
        }

        .mail {
            border: 1px solid white;
            border-radius: 6px;
        }

        .msg {
            border: 1px solid white;
            border-radius: 6px;
        }

        .info {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

        .separator {
            border: 1px solid white;
            margin: 24px auto;
            width: 30%;
        }

        button {
            padding: 0.688rem 1.563rem;
            border: 0px;
            border-radius: 0.375rem;

            font-size: 0.938rem;
            letter-spacing: -1.5%;
            font-weight: 500;
        }
    }

</style>

<h1 style="text-align: center; font-weight: 900;">ME CONTACTER</h1>

<div class="separator"></div>

<div class="desktop">
    <form action="" method="get" style="display: flex; flex-direction: column; gap: 15px">
        <div class="info">
            <input type="text" placeholder="Nom" class="name">
            <input type="text" placeholder="Email" class="mail">
        </div>
        <textarea placeholder="Votre message" cols="40" rows="5" class="msg"></textarea>
        <button type="button">Envoyer</button>
    </form>
</div>

<div class="mobile">
<form action="" method="get" style="display: flex; flex-direction: column; gap: 15px">
    <input type="text" placeholder="Nom" class="name">
    <input type="text" placeholder="Email" class="mail">
    <textarea placeholder="Votre message" cols="15" rows="5" class="msg"></textarea>
    <button type="button">Envoyer</button>
</form>
</div>