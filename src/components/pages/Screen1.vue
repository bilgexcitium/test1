<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="9d9df1d9-29b1-4e9b-ac20-adbaafb38e04"
    v-bind:style="{'width':'100%','height':'auto'}">
    <LottieDeer src="https://assets10.lottiefiles.com/packages/lf20_d9zzaK1MTt.json" v-bind:loop="false"
      v-bind:count="0" v-bind:hover="false" v-bind:speed="1" v-bind:rotate="0" v-bind:autoplay="true"
      v-bind:direction="1" v-bind:openCount="false" background="transparent" animationName="" ncTooltipText=""
      position="relative" v-bind:snapX="false" v-bind:snapY="false" id="38815e5f-7120-45f1-90c5-4b1681600148"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','marginTop':'0px','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#000000','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'0px','paddingBottom':'0px','backdropFilter':'none','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@import 'src/assets/styles/scroll';
 @include custom-scroll();
@media (min-width: 1024.05px){
[id='9d9df1d9-29b1-4e9b-ac20-adbaafb38e04'] {
             display: grid; 
             grid-template-columns: 46.30859375rem 14.0625rem 39.62890625rem;
             grid-template-rows: minmax(44.4921875rem, max-content) minmax(14.0625rem, max-content) minmax(33.5546875rem, max-content);
          }
[id='38815e5f-7120-45f1-90c5-4b1681600148']{
          grid-area: 2/2/3/3;
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='9d9df1d9-29b1-4e9b-ac20-adbaafb38e04'] {
             display: grid; 
             grid-template-columns: 41.2109375rem 17.578125rem 41.2109375rem;
             grid-template-rows: minmax(55.615234375rem, max-content) minmax(17.578125rem, max-content) minmax(3.125rem, max-content);
          }
[id='38815e5f-7120-45f1-90c5-4b1681600148']{
          grid-area: 2/2/3/3;
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='9d9df1d9-29b1-4e9b-ac20-adbaafb38e04'] {
             display: grid; 
             grid-template-columns: 38.28125rem 23.4375rem 38.28125rem;
             grid-template-rows: minmax(74.15364583333333rem, max-content) minmax(23.4375rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='38815e5f-7120-45f1-90c5-4b1681600148']{
          grid-area: 2/2/3/3;
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='9d9df1d9-29b1-4e9b-ac20-adbaafb38e04'] {
             display: grid; 
             grid-template-columns: 31.25rem 37.5rem 31.25rem;
             grid-template-rows: minmax(118.64583333333333rem, max-content) minmax(37.5rem, max-content) minmax(5rem, max-content);
          }
[id='38815e5f-7120-45f1-90c5-4b1681600148']{
          grid-area: 2/2/3/3;
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='9d9df1d9-29b1-4e9b-ac20-adbaafb38e04'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: minmax(151.86666666666667rem, max-content) minmax(87.2rem, max-content) minmax(6.4rem, max-content);
          }
[id='38815e5f-7120-45f1-90c5-4b1681600148']{
          grid-area: 2/2/3/3;
          }
}
</style>