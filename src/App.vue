<template>
  <ion-app>


    <Menu></Menu>


    <ion-page id="main-content">
      <ion-header>
        <ion-toolbar>
          <ion-grid>
            <ion-row>
              <ion-buttons>
                <ion-menu-button></ion-menu-button>
              </ion-buttons>
              <ion-icon :icon="leaf" size="large" style="color: var(--ion-color-primary); margin-top: 5px; margin-left: 20px;"></ion-icon>
              <ion-title>Geno's Forest Grove</ion-title>
            </ion-row>
          </ion-grid>
        </ion-toolbar>
      </ion-header>


      <ion-content>
        <img src="../assets/pexels-mikechie-esparagoza-16017742.jpg" alt="">
        <ion-grid>
          <ion-row>
            <ion-icon :icon="star" size="large" style="color: var(--ion-color-primary); margin-top: 18px; margin-left: 20px;"></ion-icon>
            <ion-title><h1>Jogos maneiros</h1></ion-title>
          </ion-row>

          <hr style="background-color:var(--ion-color-primary); margin: 10px;">

          <ion-row>
            <GameComponent
              title="Chrono Trigger"
              subtitle="1995 | Super Nintendo"
              description="Chrono Trigger é um jogo de RPG eletrônico desenvolvido pela Square Co. Foi lançado para o console Super Nintendo no Japão em março de 1995, e uma versão aprimorada para PlayStation foi lançada em novembro de 1999."
              image="https://s2.glbimg.com/AngmlHc6lDIKw0Pqsxh0Q-ghssg=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/F/o/6uYQ8ASBmnIQkxYBe5JA/2016-03-16-chrono-trigge-wallpaper.jpg"
              id="chrono-trigger"
              video="../../assets/videos/CHRONO TRIGGER – Launch Trailer.mp4"/>

            <GameComponent
              title="Hades"
              subtitle="2016 | Xbox One"
              description="Hades é um jogo eletrônico roguelike de RPG de ação desenvolvido e publicado pela Supergiant Games. Foi lançado para Microsoft Windows, macOS e Nintendo Switch em 17 de setembro de 2020, após um lançamento de acesso antecipado em dezembro de 2018."
              image="https://tm.ibxk.com.br/2021/08/09/09233636296464.jpg"
              id="hades"
              video="../../assets/videos/Hades - Official Animated Trailer.mp4"/>

            <GameComponent
              title="Hue"
              subtitle="2019 | Xbox One"
              description="Hue é um jogo de plataforma de quebra-cabeça de 2016 projetado por Henry Hoffman e Dan Da Rocha, desenvolvido pela Fiddlesticks e publicado pela Curve Digital."
              image="https://img.hype.games/cdn/59a24f9a-02d6-4831-8580-d6e7192d9dd2Cover-600.jpg"
              id="hue"
              video="../../assets/videos/Hue - Coming Soon Trailer PS4 PS Vita Xbox One .mp4"/>
          </ion-row>


          <ion-row>
            <GameComponent
              title="The Legend of Zelda: Twilight Princess"
              subtitle="2006 | Nintendo GameCube"
              description="The Legend of Zelda: Twilight Princess é um jogo eletrônico de ação-aventura desenvolvido pela Nintendo EAD, e publicado pela Nintendo para o GameCube e Wii."
              image="https://i0.wp.com/mynintendonews.com/wp-content/uploads/2015/04/zelda_twilight_princess.jpg?fit=1280%2C1024&ssl=1"
              id="zelda-twilight"
              video="../../assets/videos/The Legend of Zelda - Twilight Princess HD Official Story Trailer(1).mp4"/>

            <GameComponent
              title="Super Paper Mario RPG: Legend of the Seven Stars"
              subtitle="1996 | Super Nintendo"
              description="Super Mario RPG é um jogo de RPG, desenvolvido pela Square, juntamente com a Nintendo e lançado em 1996 no Japão e nos Estados Unidos para o Super NES. O jogo é o primeiro RPG a estrelar o mascote da Nintendo, Mario, e por 7 anos, o último jogo da Square em um console da Nintendo."
              image="https://i0.wp.com/www.the-pixels.com/wp-content/uploads/2017/02/smrpglotsssm.jpg?fit=1203%2C915&ssl=1"
              id="mario-rpg"
              video="../../assets/videos/Super Mario RPG Trailer.mp4"/>

            <GameComponent
              title="Super Paper Mario"
              subtitle="2007 | Nintendo Wii"
              description="Super Paper Mario é um jogo eletrônico misto de plataforma e RPG produzido pela Intelligent Systems. Foi planejado para o GameCube, mas com a chegada do Wii, a Nintendo lançou-o no novo console. Traz personagens do Reino dos Cogumelos em uma aventura com toques de RPG e plataforma."
              image="https://i.pinimg.com/originals/b6/b7/f5/b6b7f5fcf7da9721deb95ba0717418a7.jpg"
              id="super-paper-mario"
              video="../../assets/videos/Super Paper Mario Nintendo Wii Trailer - From 2D to 3D.mp4"/>
          </ion-row>


          <ion-row>
            <GameComponent
              title="Star Fox"
              subtitle="1993 | Super Nintendo"
              description="Star Fox, conhecido como Starwing nas regiões PAL, é um videogame rail shooter desenvolvido pela Nintendo e Argonaut Software e publicado pela Nintendo para o Super Nintendo Entertainment System."
              image="https://s2.glbimg.com/d1EpVG5NaF7C2auIeZP7Lk69ckc=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/0/2/wRrBKfSnWuzpBb4oAhGQ/2016-03-22-super-nes-s-25th-anniversary-have-you-played-any-of-these-15-essential-games-721102.jpg"
              id="starfox"
              video="../../assets/videos/Star Fox SNES Commercial - Retro Game Trailers.mp4"/>

            <GameComponent
              title="OneShot"
              subtitle="2016 | PC"
              description="OneShot é um jogo de aventura desenvolvido pelo estúdio independente Future Cat e publicado pela Degica. Baseado em uma versão gratuita de 2014, foi lançado para Steam em 8 de dezembro de 2016 e no itch.io em 12 de março de 2020."
              image="https://cdn.akamai.steamstatic.com/steam/apps/420530/capsule_616x353.jpg?t=1681246342"
              id="one-shot"
              video="../../assets/videos/OneShot Trailer.mp4"/>

            <!-- <GameComponent
              title="The Prison Boys"
              subtitle="2017 | Mobile"
              description="É o final da era Taisho. O personagem principal, Tetsu Akatsuki, testemunha um incidente na prisão de 12 andares, que é um dos centros da Polícia Secreta... Quanto mais perto ele chega da verdade, mais ele descobre que a escuridão da prisão de 12 andares é profunda. Mantendo seu próprio senso de justiça em mente, resolva os mistérios junto com seu parceiro! O jogo de aventura e mistério sobre a justiça e a amizade entre Tetsu e Nagi, que colocam suas vidas em risco."
              image="https://modyolo.com/wp-content/uploads/2022/09/the-prison-boys-1.jpg"
              id="prison-boys"
              video="../../assets/videos/Mystery novel and Escape Game [The Prison Boys].mp4"/> -->

            <GameComponent
              title="Bug Fables: The Everlasting Sapling"
              subtitle="2019 | Xbox One"
              description="Bug Fables: The Everlasting Sapling é um videogame de RPG desenvolvido pelo estúdio independente panamenho Moonsprout Games e publicado pela Dangen Entertainment."
              image="https://i.ytimg.com/vi/jag9W4X6yTM/maxresdefault.jpg"
              id="bug-fable"
              video="../../assets/videos/Bug Fables - The Everlasting Sapling - PC Release Trailer.mp4"/>

            <!-- <GameComponent
              title="Deltarune"
              subtitle="2019 | PC"
              description="Deltarune é um jogo de RPG criado pelo desenvolvedor indie norte-americano Toby Fox. O jogador controla um humano, Kris, em um mundo onde os monstros vivem na superfície da Terra."
              image="https://files.tecnoblog.net/wp-content/uploads/2021/09/deltarune.jpg"
              id="deltarune"
              video="../../assets/videos/Deltarune Chapter 2 Trailer!.mp4"/> -->

            <!-- <GameComponent
              title="Bug Fables: The Everlasting Sapling"
              subtitle="2022 | Xbox One"
              description="Bug Fables: The Everlasting Sapling é um videogame de RPG desenvolvido pelo estúdio independente panamenho Moonsprout Games e publicado pela Dangen Entertainment."
              image="https://i.ytimg.com/vi/jag9W4X6yTM/maxresdefault.jpg"
              id="bug-fable"
              video="../../assets/videos/Bug Fables - The Everlasting Sapling - PC Release Trailer.mp4"/> -->
          </ion-row>

          <!-- <ion-row>
            <GameComponent
              title="OneShot"
              subtitle="2017 | PC"
              description="OneShot é um jogo de aventura desenvolvido pelo estúdio independente Future Cat e publicado pela Degica. Baseado em uma versão gratuita de 2014, foi lançado para Steam em 8 de dezembro de 2016 e no itch.io em 12 de março de 2020."
              image="https://cdn.akamai.steamstatic.com/steam/apps/420530/capsule_616x353.jpg?t=1681246342"
              id="one-shot"
              video="../../assets/videos/OneShot Trailer.mp4"/>

            <GameComponent
              title="The Prison Boys"
              subtitle="2022 | Mobile"
              description="É o final da era Taisho. O personagem principal, Tetsu Akatsuki, testemunha um incidente na prisão de 12 andares, que é um dos centros da Polícia Secreta... Quanto mais perto ele chega da verdade, mais ele descobre que a escuridão da prisão de 12 andares é profunda. Mantendo seu próprio senso de justiça em mente, resolva os mistérios junto com seu parceiro! O jogo de aventura e mistério sobre a justiça e a amizade entre Tetsu e Nagi, que colocam suas vidas em risco."
              image="https://modyolo.com/wp-content/uploads/2022/09/the-prison-boys-1.jpg"
              id="prison-boys"
              video="../../assets/videos/Mystery novel and Escape Game [The Prison Boys].mp4"/>

            <GameComponent
              title="Mass Effect"
              subtitle="2007 | PC"
              description="Mass Effect se passa no ano de 2183. O jogador assume o controle de um soldado de elite chamado Shepard, que é mandado em missões de exploração pela galáxia em uma nave espacial, chamada Normandy. O título Mass Effect faz referência a uma tecnologia presente no jogo, que permite a viagem em uma velocidade mais rápida que a luz."
              image="https://cdn.akamai.steamstatic.com/steam/apps/17460/capsule_616x353.jpg?t=1684225163"
              id="mass-effect"
              video="../../assets/videos/Mass Effect 1 Trailer.mp4"/>
          </ion-row> -->
        </ion-grid>
      </ion-content>
    </ion-page>
    <ion-router-outlet id="content"></ion-router-outlet>
  </ion-app>
</template>

<script setup lang="ts">
import { heart, leaf, logoIonic, star } from 'ionicons/icons';
import {
  IonApp,
  IonContent,
  IonIcon,
  IonMenu,
  IonHeader,
  IonTitle,
  IonToolbar,
  IonButtons,
  IonMenuButton,
  IonPage
} from '@ionic/vue';
import { defineComponent, ref } from 'vue';
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
import GameComponent from './views/GameComponent.vue';
import Menu from './views/Menu.vue';
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
