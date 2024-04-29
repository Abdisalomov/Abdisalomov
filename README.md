<style>
        * {
    margin: 0;
    padding: 0;
    }

        body {
            /* font-family: sans-serif; */
        font-family: "Dancing Script", cursive;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #111;
        }

        .loader {
            font-size: 78px;
            /* text-transform: uppercase; */
            color: aqua;
            animation: animate 5s ease-in-out infinite;
        }



        @keyframes animate {
            0% {
                transform: scale(0.8);
            }
            10% {
                color: yellow;
                transform: rotate(-90deg);
            }
            20% {
                color: green;
                transform: rotate(90deg);
            }
            30% {
                color: pink;
            }
            40% {
                color: blue;
            }
            50% {
                color: orange;
                transform: rotate(1440deg);
            }
            60% {
                color: darkred;
            }
            70% {
                color: darkblue;
            }
            80% {
                color: yellowgreen;
            }
            90% {
                color: orangered;
            }
            100% {
                color: aqua;
                transform: scale(1.5);
            }
        }

        .loader span:nth-child(1) {
            animation-delay: 0.8s;
        }

        .loader span:nth-child(2) {
            animation-delay: 1s;
        }

        .loader span:nth-child(3) {
            animation-delay: 1.2s;
        }

        .loader span:nth-child(4) {
            animation-delay: 1.4s;
        }

        .loader span:nth-child(5) {
            animation-delay: 1.6s;
        }

        .loader span:nth-child(6) {
            animation-delay: 1.8s;
        }

        .loader span:nth-child(7) {
            animation-delay: 2s;
        }

        .loader span:nth-child(8) {
            animation-delay: 2.2s;
        }

        .loader span:nth-child(9) {
            animation-delay: 2.4s;
        }

        .loader span:nth-child(10) {
            animation-delay: 2.6s;
        }


    </style>
<div class="loader" id="loader">
        <span>F</span>
        <span>r</span>
        <span>o</span>
        <span>n</span>
        <span>t</span>
        <span>E</span>
        <span>n</span>
        <span>d</span>
    </div>

- 👀 I’m interested in Front End
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

