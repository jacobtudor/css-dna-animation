# css-dna-animation
Animation produced utilising html and css. Vue component ready for implementation produced from this code. 

<svg fill="none" width="100%"  xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>dnacomponent</title>
        <link rel="stylesheet" href="dna.css">
    </head>
    <body style="display:flex; justify-content:center">
        <div class="dna">
            <div class="row row1">
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 2;"></div>
                    <div class="line" style="--i: 2;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 3;"></div>
                    <div class="line" style="--i: 3;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 4;"></div>
                    <div class="line" style="--i: 4;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 5;"></div>
                    <div class="line" style="--i: 5;"></div>
                </div>
            </div>
            <div class="row row2">
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 1;"></div>
                    <div class="line" style="--i: 1;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 2;"></div>
                    <div class="line" style="--i: 2;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 3;"></div>
                    <div class="line" style="--i: 3;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 4;"></div>
                    <div class="line" style="--i: 4;"></div>
                </div>
                <div class="strand">
                    <div class="circle" style="--i: 5;"></div>
                    <div class="line" style="--i: 5;"></div>
                </div>
            </div>
        </div>
    </body>
    </html>
    <style>
        .row {
            display: flex;
            }

            .row1 .strand {
            flex-direction: column-reverse;
            }

            .row2 .strand {
            flex-direction: column;
            }

            .strand {
            position: relative;
            display: flex;
            align-items: center;
            height: 2rem;
            padding: 0 1px;
            }

            .circle {
            position: absolute;
            background-color: green;
            width: 3px;
            height: 3px;
            border-radius: 50%;
            }

            .row1 .circle, .row2 .circle {
            animation-duration: 5000ms;
            animation-iteration-count: infinite;
            animation-timing-function: linear;
            }
            .row1 .strand:nth-child(1) .circle, .row1 .strand:nth-child(1) .line, .row2 .strand:nth-child(1) .circle, .row2 .strand:nth-child(1) .line {
            animation-delay: 0ms;
            }
            .row1 .strand:nth-child(2) .circle, .row1 .strand:nth-child(2) .line, .row2 .strand:nth-child(2) .circle, .row2 .strand:nth-child(2) .line {
            animation-delay: 250ms;
            }
            .row1 .strand:nth-child(3) .circle, .row1 .strand:nth-child(3) .line, .row2 .strand:nth-child(3) .circle, .row2 .strand:nth-child(3) .line {
            animation-delay: 500ms;
            }
            .row1 .strand:nth-child(4) .circle, .row1 .strand:nth-child(4) .line, .row2 .strand:nth-child(4) .circle, .row2 .strand:nth-child(4) .line {
            animation-delay: 750ms;
            }
            .row1 .strand:nth-child(5) .circle, .row1 .strand:nth-child(5) .line, .row2 .strand:nth-child(5) .circle, .row2 .strand:nth-child(5) .line {
            animation-delay: 1000ms;
            }
            .row1 .strand:nth-child(6) .circle, .row1 .strand:nth-child(6) .line, .row2 .strand:nth-child(6) .circle, .row2 .strand:nth-child(6) .line {
            animation-delay: 1250ms;
            }
            .row1 .strand:nth-child(7) .circle, .row1 .strand:nth-child(7) .line, .row2 .strand:nth-child(7) .circle, .row2 .strand:nth-child(7) .line {
            animation-delay: 1500ms;
            }
            .row1 .strand:nth-child(8) .circle, .row1 .strand:nth-child(8) .line, .row2 .strand:nth-child(8) .circle, .row2 .strand:nth-child(8) .line {
            animation-delay: 1750ms;
            }
            .row1 .strand:nth-child(9) .circle, .row1 .strand:nth-child(9) .line, .row2 .strand:nth-child(9) .circle, .row2 .strand:nth-child(9) .line {
            animation-delay: 2000ms;
            }
            .row1 .strand:nth-child(10) .circle, .row1 .strand:nth-child(10) .line, .row2 .strand:nth-child(10) .circle, .row2 .strand:nth-child(10) .line {
            animation-delay: 2250ms;
            }

            .row1 .circle {
            top: 0%;
            animation-name: row1circletwist;
            }

            .row2 .circle {
            bottom: 0%;
            animation-name: row2circletwist;
            }

            @keyframes row1circletwist {
            0% {
                background-color: green;
                scale: 1;
                top: 0%;
            }
            25% {
                background-color: greenyellow;
                scale: 0.75;
                top: calc(100% - 3px);
            }
            50% {
                background-color: greenyellow;
                scale: 0.5;
                top: calc(200% - 3px);
            }
            75% {
                background-color: greenyellow;
                scale: 0.75;
                top: calc(100% - 3px);
            }
            100% {
                background-color: green;
                scale: 1;
                top: 0%;
            }
            }
            @keyframes row2circletwist {
            0% {
                background-color: green;
                scale: 1;
                bottom: 0%;
            }
            25% {
                background-color: greenyellow;
                scale: 0.75;
                bottom: calc(100% - 3px);
            }
            50% {
                background-color: greenyellow;
                scale: 0.5;
                bottom: calc(200% - 3px);
            }
            75% {
                background-color: greenyellow;
                scale: 0.75;
                bottom: calc(100% - 3px);
            }
            100% {
                background-color: green;
                scale: 1;
                bottom: 0%;
            }
            }
            .line {
            width: 2px;
            height: 80%;
            margin: 1px 2px;
            background-color: rgb(88, 241, 88);
            animation-name: linescale;
            animation-duration: 5000ms;
            animation-iteration-count: infinite;
            animation-timing-function: linear;
            }

            @keyframes linescale {
            0% {
                background-color: green;
                height: 80%;
            }
            24% {
                animation-play-state: running;
            }
            25% {
                background-color: greenyellow;
                height: 0%;
            }
            26% {
                animation-play-state: running;
            }
            50% {
                background-color: green;
                height: 80%;
            }
            74% {
                animation-play-state: running;
            }
            75% {
                background-color: greenyellow;
                height: 0%;
            }
            76% {
                animation-play-state: running;
            }
            100% {
                background-color: green;
                height: 80%;
            }
            }

            /*# sourceMappingURL=dna.css.map */

    <style/>
 </foreignObject>
</svg>