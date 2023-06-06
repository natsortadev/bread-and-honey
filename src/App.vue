<template>
  <ion-app>
    <ion-header>
      <ion-toolbar>
        <ion-grid>
          <ion-title>Geno's Forest Grove</ion-title>
        </ion-grid>
      </ion-toolbar>
    </ion-header>


    <ion-content>
      <img src="../assets/pexels-mikechie-esparagoza-16017742.jpg" alt="">
      <ion-grid>
        <ion-row>
          <ion-icon :icon="star" size="large" style="color: var(--ion-color-primary); margin-top: 18px; margin-left: 20px;"></ion-icon>
          <ion-title><h1>Top 9 da Nat</h1></ion-title>
        </ion-row>

        <hr style="background-color:var(--ion-color-primary); margin: 10px;">

        <ion-row>
          <ion-col>
            <ion-card button="true">
              <img alt="Chrono Trigger" src="https://s2.glbimg.com/AngmlHc6lDIKw0Pqsxh0Q-ghssg=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/F/o/6uYQ8ASBmnIQkxYBe5JA/2016-03-16-chrono-trigge-wallpaper.jpg" />
              <ion-card-header>
                <ion-card-title>Chrono Trigger</ion-card-title>
                <ion-card-subtitle>2021 | zsnes</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Chrono Trigger é um jogo de RPG eletrônico desenvolvido pela Square Co. Foi lançado para o console Super Nintendo no Japão em março de 1995, e uma versão aprimorada para PlayStation foi lançada em novembro de 1999.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Hades" src="https://tm.ibxk.com.br/2021/08/09/09233636296464.jpg" />
              <ion-card-header>
                <ion-card-title>Hades</ion-card-title>
                <ion-card-subtitle>2022 | Xbox One</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Hades é um jogo eletrônico roguelike de RPG de ação desenvolvido e publicado pela Supergiant Games. Foi lançado para Microsoft Windows, macOS e Nintendo Switch em 17 de setembro de 2020, após um lançamento de acesso antecipado em dezembro de 2018.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Hue" src="https://img.hype.games/cdn/59a24f9a-02d6-4831-8580-d6e7192d9dd2Cover-600.jpg" />
              <ion-card-header>
                <ion-card-title>Hue</ion-card-title>
                <ion-card-subtitle>2019 | Xbox One</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Hue é um jogo de plataforma de quebra-cabeça de 2016 projetado por Henry Hoffman e Dan Da Rocha, desenvolvido pela Fiddlesticks e publicado pela Curve Digital.
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>

        <ion-row>
          <ion-col>
            <ion-card button="true">
              <img alt="The Legend of Zelda: Twilight Princess" src="https://i0.wp.com/mynintendonews.com/wp-content/uploads/2015/04/zelda_twilight_princess.jpg?fit=1280%2C1024&ssl=1" />
              <ion-card-header>
                <ion-card-title>The Legend of Zelda: Twilight Princess</ion-card-title>
                <ion-card-subtitle>2018 | Nintendo Wii</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                The Legend of Zelda: Twilight Princess é um jogo eletrônico de ação-aventura desenvolvido pela Nintendo EAD, e publicado pela Nintendo para o GameCube e Wii.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Super Paper Mario RPG: Legend of the Seven Stars" src="https://i0.wp.com/www.the-pixels.com/wp-content/uploads/2017/02/smrpglotsssm.jpg?fit=1203%2C915&ssl=1" />
              <ion-card-header>
                <ion-card-title>Super Paper Mario RPG: Legend of the Seven Stars</ion-card-title>
                <ion-card-subtitle>2023 | zsnes</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Super Mario RPG é um jogo de RPG, desenvolvido pela Square, juntamente com a Nintendo e lançado em 1996 no Japão e nos Estados Unidos para o Super NES. O jogo é o primeiro RPG a estrelar o mascote da Nintendo, Mario, e por 7 anos, o último jogo da Square em um console da Nintendo.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Super Paper Mario" src="https://i.pinimg.com/originals/b6/b7/f5/b6b7f5fcf7da9721deb95ba0717418a7.jpg" />
              <ion-card-header>
                <ion-card-title>Super Paper Mario</ion-card-title>
                <ion-card-subtitle>2016 | Nintendo Wii</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Super Paper Mario é um jogo eletrônico misto de plataforma e RPG produzido pela Intelligent Systems. Foi planejado para o GameCube, mas com a chegada do Wii, a Nintendo lançou-o no novo console. Traz personagens do Reino dos Cogumelos em uma aventura com toques de RPG e plataforma.
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>

        <ion-row>
          <ion-col>
            <ion-card button="true">
              <img alt="Star Fox" src="https://s2.glbimg.com/d1EpVG5NaF7C2auIeZP7Lk69ckc=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/0/2/wRrBKfSnWuzpBb4oAhGQ/2016-03-22-super-nes-s-25th-anniversary-have-you-played-any-of-these-15-essential-games-721102.jpg" />
              <ion-card-header>
                <ion-card-title>Star Fox</ion-card-title>
                <ion-card-subtitle>2022 | zsnes</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Star Fox, conhecido como Starwing nas regiões PAL, é um videogame rail shooter desenvolvido pela Nintendo e Argonaut Software e publicado pela Nintendo para o Super Nintendo Entertainment System.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Deltarune" src="https://files.tecnoblog.net/wp-content/uploads/2021/09/deltarune.jpg" />
              <ion-card-header>
                <ion-card-title>Deltarune</ion-card-title>
                <ion-card-subtitle>2019 | PC</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Deltarune é um jogo de RPG criado pelo desenvolvedor indie norte-americano Toby Fox. O jogador controla um humano, Kris, em um mundo onde os monstros vivem na superfície da Terra.              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="Bug Fables: The Everlasting Sapling" src="https://i.ytimg.com/vi/jag9W4X6yTM/maxresdefault.jpg" />
              <ion-card-header>
                <ion-card-title>Bug Fables: The Everlasting Sapling</ion-card-title>
                <ion-card-subtitle>2022 | Xbox One</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Bug Fables: The Everlasting Sapling é um videogame de RPG desenvolvido pelo estúdio independente panamenho Moonsprout Games e publicado pela Dangen Entertainment.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <!-- <ion-col>
            <ion-card button="true">
              <img alt="The Prison Boys" src="../assets/mqdefault.jpg" />
              <ion-card-header>
                <ion-card-title>The Prison Boys</ion-card-title>
                <ion-card-subtitle>2022 | Mobile</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                Here's a small text description for the card content. Nothing more, nothing less.
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col>
            <ion-card button="true">
              <img alt="OneShot" src="https://upload.wikimedia.org/wikipedia/en/8/81/OneShot_cover_art.png" />
              <ion-card-header>
                <ion-card-title>OneShot</ion-card-title>
                <ion-card-subtitle>2017 | PC</ion-card-subtitle>
              </ion-card-header>
              <ion-card-content>
                OneShot é um jogo de aventura desenvolvido pelo estúdio independente Future Cat e publicado pela Degica. Baseado em uma versão gratuita de 2014, foi lançado para Steam em 8 de dezembro de 2016 e no itch.io em 12 de março de 2020.
              </ion-card-content>
            </ion-card>
          </ion-col> -->
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-app>
</template>

<script setup lang="ts">
import { heart, logoIonic, star } from 'ionicons/icons';
import {
  IonApp,
  IonContent,
  IonIcon,
  IonItem,
  IonLabel,
  IonList,
  IonListHeader,
  IonMenu,
  IonMenuToggle,
  IonNote,
  IonRouterOutlet,
  IonSplitPane,
} from '@ionic/vue';
import { ref } from 'vue';
import {
  archiveOutline,
  archiveSharp,
  bookmarkOutline,
  bookmarkSharp,
  heartOutline,
  heartSharp,
  mailOutline,
  mailSharp,
  paperPlaneOutline,
  paperPlaneSharp,
  trashOutline,
  trashSharp,
  warningOutline,
  warningSharp,
} from 'ionicons/icons';
</script>

<style scoped>
ion-menu ion-content {
  --background: var(--ion-item-background, var(--ion-background-color, #fff));
}

ion-menu.md ion-content {
  --padding-start: 8px;
  --padding-end: 8px;
  --padding-top: 20px;
  --padding-bottom: 20px;
}

ion-menu.md ion-list {
  padding: 20px 0;
}

ion-menu.md ion-note {
  margin-bottom: 30px;
}

ion-menu.md ion-list-header,
ion-menu.md ion-note {
  padding-left: 10px;
}

ion-menu.md ion-list#inbox-list {
  border-bottom: 1px solid var(--ion-color-step-150, #d7d8da);
}

ion-menu.md ion-list#inbox-list ion-list-header {
  font-size: 22px;
  font-weight: 600;

  min-height: 20px;
}

ion-menu.md ion-list#labels-list ion-list-header {
  font-size: 16px;

  margin-bottom: 18px;

  color: #757575;

  min-height: 26px;
}

ion-menu.md ion-item {
  --padding-start: 10px;
  --padding-end: 10px;
  border-radius: 4px;
}

ion-menu.md ion-item.selected {
  --background: rgba(var(--ion-color-primary-rgb), 0.14);
}

ion-menu.md ion-item.selected ion-icon {
  color: var(--ion-color-primary);
}

ion-menu.md ion-item ion-icon {
  color: #616e7e;
}

ion-menu.md ion-item ion-label {
  font-weight: 500;
}

ion-menu.ios ion-content {
  --padding-bottom: 20px;
}

ion-menu.ios ion-list {
  padding: 20px 0 0 0;
}

ion-menu.ios ion-note {
  line-height: 24px;
  margin-bottom: 20px;
}

ion-menu.ios ion-item {
  --padding-start: 16px;
  --padding-end: 16px;
  --min-height: 50px;
}

ion-menu.ios ion-item.selected ion-icon {
  color: var(--ion-color-primary);
}

ion-menu.ios ion-item ion-icon {
  font-size: 24px;
  color: #73849a;
}

ion-menu.ios ion-list#labels-list ion-list-header {
  margin-bottom: 8px;
}

ion-menu.ios ion-list-header,
ion-menu.ios ion-note {
  padding-left: 16px;
  padding-right: 16px;
}

ion-menu.ios ion-note {
  margin-bottom: 8px;
}

ion-note {
  display: inline-block;
  font-size: 16px;

  color: var(--ion-color-medium-shade);
}

ion-item.selected {
  --color: var(--ion-color-primary);
}
</style>
