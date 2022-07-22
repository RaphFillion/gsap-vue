<template>
  <div class="demo">
    <div class="container">
      <div class="cube cube-1"></div>
      <div class="cube cube-2"></div>
      <div class="cube cube-3"></div>
      <div class="cube cube-4"></div>
    </div>
    <div class="scrollTrigger">
      <p class="text text-1">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo, pariatur? Vel rem, sint voluptatem pariatur suscipit ad fugit minus quo ab id, inventore aliquid fugiat labore, soluta perspiciatis quod? Maiores esse quisquam at consectetur porro explicabo fuga saepe expedita dolorum ratione dolor, quod modi non tempore autem magni aut laboriosam, dolore veniam consequuntur quaerat laborum aliquid. Debitis, sit dolor. Sit eos architecto suscipit illo dicta optio ullam eaque officiis distinctio. Quibusdam, nisi suscipit minima corporis repellat alias quaerat in perspiciatis quos architecto, nihil neque assumenda quae adipisci fuga ex eos, aliquam inventore laudantium deserunt libero sapiente labore asperiores. Pariatur vitae excepturi est atque obcaecati autem molestiae assumenda repellendus, numquam aliquam distinctio facilis quia, nihil veniam. Ipsam earum molestiae officiis perferendis neque ducimus explicabo, commodi quod! Veniam iusto repellendus harum, aliquam asperiores qui quo quidem incidunt dolorem quisquam tenetur delectus autem voluptas eveniet ullam? Ea asperiores accusantium aut, non sapiente amet deleniti pariatur excepturi a deserunt consectetur beatae dolores id! Nostrum tempora praesentium, qui aspernatur asperiores nulla possimus! Modi, impedit beatae culpa odit maxime, nemo tenetur voluptatum doloremque, possimus voluptatibus corporis nostrum illo molestias quae quod. Sed dignissimos mollitia iure officia nulla eius blanditiis, dicta eveniet consequatur culpa temporibus. Repellendus, ducimus.
      </p>
      <p class="text text-2">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum quo quae odio porro esse quaerat repellendus debitis magni in unde repudiandae, aspernatur corrupti consequatur commodi distinctio officiis optio delectus dignissimos. Maxime quia autem quis assumenda debitis veniam quaerat tempora eligendi expedita minus architecto sit explicabo dolore, dolor commodi aut asperiores! Cumque magnam eum sed eaque? Cumque praesentium nemo repellendus quibusdam sequi, reprehenderit ut, animi ex laboriosam impedit vel deleniti quidem. Harum eos earum quo, tempore quia officia odio excepturi sunt distinctio vero tempora aliquid officiis iusto consequatur eveniet voluptatum eligendi, magni ea. Delectus libero nihil rerum voluptas, laudantium necessitatibus repellat consequatur laboriosam excepturi commodi quas fuga veritatis quidem hic adipisci maxime autem quae eaque doloribus aliquid ipsam incidunt sapiente saepe eligendi. Culpa earum odio aspernatur debitis harum qui distinctio natus ab vel assumenda sint quibusdam, minima officiis maxime! Harum veniam voluptate quasi in eos quae labore deleniti nihil sit illum!
      </p>
      <p class="text text-3">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Commodi temporibus optio aspernatur ducimus quasi facere possimus modi ea porro non, ratione debitis voluptatum voluptates pariatur incidunt molestiae quo obcaecati vitae dolorem aperiam exercitationem sint praesentium expedita. Et culpa aliquid excepturi maiores cumque vero consectetur quis! Sed possimus rerum similique suscipit eaque, consequuntur, aliquam delectus, eos dignissimos fugit architecto voluptatum explicabo veritatis est! Commodi cum sequi eaque quae aspernatur dolore cumque omnis iusto ipsa, doloremque quaerat consequuntur mollitia magnam in perferendis placeat unde error officia aliquid illo explicabo porro? Reprehenderit, ratione perferendis quidem illum commodi sequi nam incidunt recusandae exercitationem iure officia quo vero ipsa magni voluptate neque tempore at explicabo ipsum? Ducimus obcaecati iusto quasi nisi officiis rem eligendi libero pariatur, aliquam fuga sit impedit? Neque non alias optio? Illo iusto temporibus perferendis repellendus ad animi reprehenderit necessitatibus quam inventore, nam aperiam ab alias velit similique vel natus unde quasi nisi autem, repellat recusandae non, asperiores vitae voluptate! Explicabo facilis enim adipisci, odio eos mollitia assumenda animi labore maiores consectetur vitae corporis voluptate quis recusandae accusantium illum voluptates ullam magni accusamus tenetur? Tenetur nostrum magnam officiis! Quidem ipsum suscipit fugit dolorum quibusdam voluptatem numquam obcaecati enim, ut ea magni id nesciunt, exercitationem quo fugiat corrupti repudiandae quod optio beatae accusantium itaque odit officiis qui pariatur. Nam, enim natus. Incidunt ratione, voluptatibus est sapiente consectetur reiciendis? Illum sunt quasi, error, magni voluptas assumenda labore quia similique quod officiis dicta. Delectus quis eos rem aperiam unde placeat porro necessitatibus quisquam in earum, cum ducimus aut magnam sed saepe, autem vitae labore! Vitae corrupti, velit minus eos qui saepe voluptas perferendis reprehenderit illo inventore sapiente quis dicta voluptatibus natus quas nihil quo reiciendis tempore accusantium! Repellat totam reiciendis, enim doloribus quam ratione reprehenderit quod eveniet nam molestias assumenda laudantium placeat dolores recusandae nulla neque veritatis illum molestiae porro architecto rerum sapiente voluptatem? Temporibus quasi beatae iusto quam ea molestias natus! Nemo deleniti, neque dolorem possimus, fugit, minus deserunt sapiente doloribus non quisquam nostrum quas esse. Officia architecto quibusdam eum quia modi! Omnis voluptatum quos numquam aliquam rem. Deleniti nemo magni architecto inventore consectetur mollitia placeat aut, eaque soluta doloremque sit libero accusantium iusto quia autem nam at? Quo nobis nulla maxime eaque ab dolorum voluptatem saepe mollitia vitae omnis provident ex dolor error sint quos eveniet quia rem nemo beatae ut at, labore quisquam officiis cupiditate? Similique, facere explicabo rerum delectus consectetur ipsa!
      </p>
    </div>
  </div>
</template>

<script>
import { gsap, ScrollTrigger } from 'gsap/all';
gsap.registerPlugin( ScrollTrigger ); 

export default {
  name: 'demo',
  mounted() {
    // Cube 1
    gsap.to('.cube-1', {y: '100%', duration: 2, ease: 'back.out(10)', delay: 1, yoyo: true, repeat: -1})

    // Cube 2
    gsap.from('.cube-2', {y: '-100%', duration: 2, ease: 'expo.out', delay: 1, yoyo: true, repeat: -1})

    // Cube 3
    gsap.fromTo('.cube-3',
      {rotate: 0, y: 0},
      {rotate: '360deg', y: '-200%', duration: 2, ease: 'expo.out', yoyo: true, delay: 1, repeat: -1})
    
    // Cube 4
    gsap.timeline({ repeat: -1 })
      .fromTo('.cube-4',
        {opacity: 0, x: '30vw', y: 0, rotate: 0},
        {opacity: 1, x: 0, y: 0, rotate: '360deg', duration: 2, ease: 'expo.out'})
      .fromTo('.cube-4', 
        {y: 0, x: 0},
        {y: '-100vh', x: 0, duration: 2, ease: 'expo.out'})
      .fromTo('.cube-4',
        {y: '100vh', x: 0},
        {y: 0, x: 0, duration: 2, ease: 'expo.out'}, '-=1.75')
      .fromTo('.cube-4',
        {opacity: 1, y: 0, x: 0, rotate: 0},
        {opacity: 0, y: 0, x: '30vw', rotate: '360deg', duration: 2, ease: 'expo.out'})
    
    // ScrollTrigger
    gsap.timeline({
      scrollTrigger: {
        start: 'top center',
        trigger: '.text-1',
        toggleActions: 'play none none reverse',
        markers: true,
      },
    })
    .fromTo('.text-1',
      {x: '-100%', opacity: 0},
      {x: 0, opacity: 1, duration: 1, ease: 'expo.out'})
    .to('.text-1', {scale: 0.9, ease: 'power4.out'}, .5)

    gsap.timeline({
      scrollTrigger: {
        start: 'top center',
        trigger: '.text-2',
        toggleActions: 'play none none reverse',
        markers: true,
      },
    })
    .from('.text-2', {x: '100%', opacity: 0, duration: 1, ease: 'expo.out'})
    .to('.text-2', {scale: 0.9, ease: 'power4.out'}, .5)

    gsap.timeline({
      scrollTrigger: {
        start: '-10% center',
        trigger: '.text-3',
        toggleActions: 'play none none reverse',
        markers: true,
      },
    })
    .from('.text-3', {y: '25%', opacity: 0, duration: 1, ease: 'expo.out'})
    .to('.text-3', {scale: 0.9, ease: 'power4.out'}, .5)
  }
}
</script>

<style lang="scss" scoped>
  .container {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    height: 100vh;
    background-color: rgb(207, 207, 207);
    overflow: hidden;
    .cube {
      width: 200px; height: 200px;
      margin: 1rem;
      border-radius: 10px;
      &.cube-1 { background-color: blue; }
      &.cube-2 { background-color: yellow; }
      &.cube-3 { background-color: green; }
      &.cube-4 { background-color: red; }
    }
  }
  .scrollTrigger {
    width: 100%;
    height: 100%;
    background-color: rgb(28, 28, 28);
    overflow: hidden;
    padding-bottom: 275px;
    .text {
      color: rgb(174, 174, 174);
      margin: 3rem 1rem;
      font-size: 30px;
      line-height: 50px;
      font-weight: 500;
      width: 75%;
      &.text-2 { float: right}
      &.text-3 {text-align: center; margin: 0 auto; padding-top: 3rem;}
    }
  }
</style>