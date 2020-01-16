---
views:
    flash:
        region: flash
        template: anax/v2/image/default
        data:
            src: "image/frusnagrenar.jpg?width=1500&height=300&crop-to-fit&area=40,0,0,10"
            alt: "Flashimg"

    Rapport:
        region: main
        data:
            meta: 
                type: single
                route: rapport/webbplatsdesign
        template: anax/v2/article/default
    
---