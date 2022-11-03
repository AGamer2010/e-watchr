# Templates

Arquivo temporário para copiar e colar "Mais Informações".

## Overlay HTML
    <div id="ovMini">
        <div class="overlay">           
            <header>
                <div class="container">
                    <h3 class="tituloOverlay"></h3>
                    <i class="fa-regular fa-circle-xmark" onclick="overlay('idMini', 'off')"></i>
                </div>    
            </header>
            <main>
                <div class="container">
                    <p>
                    </p>
                    <button role="button" class="botao" onclick="overlay(windowOpen(''))" >
                        Acessar mais informações
                        <!-- Ícone em SVG-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="siteExterno" viewBox="0 0 16 16">
                            <path fill-rule="evenodd" d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5z"/>
                            <path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0v-5z"/>
                          </svg>
                    </button>
                </div>
            </main>
        </div>
    </div>

## Overlay CSS

#ovMini@{
    position: fixed;
    display: none;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0,0,0,0.5);
    cursor: pointer;
    z-index: 3;
    justify-content: center;
}

## Overlay JS

case 'idMini@':
            console.log(id+trigger)
            switch (trigger){
                case 'on':
                    document.getElementById("ovMini@").style.display = "block"
                    console.log(id + trigger)
                break

                case 'off':
                    document.getElementById("ovMini@").style.display = "none"
                    console.log(id + trigger)
            }
            break