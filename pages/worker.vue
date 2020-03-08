<template>
  <div class="Worker">
    <h2 class="Worker-Heading">
      企業の皆様・はたらく皆様へ
    </h2>
    <div v-for="(item, i) in items" :key="i">
      <TextCard :title="item.title" :body="item.body" />
    </div>
  </div>
</template>
<script lang="ts">
import TextCard from '@/components/TextCard.vue'
export default {
  components: {
    TextCard
  },
  data() {
    return {
      items: [
        {
          title: '中小企業向け相談窓口及び融資取扱について',
          body:
            '<a href="http://www.pref.hokkaido.lg.jp/kz/csk/kny/yuushi/korona.htm" target="_blank" rel="noopener">http://www.pref.hokkaido.lg.jp/kz/csk/kny/yuushi/korona.htm</a> <br />新型コロナウイルス関連肺炎の流行に伴う中小企業向け相談窓口及び融資取扱について'
        },
        {
          title: '新型コロナ感染症の影響による特別労働相談窓口',
          body:
            '<a href="http://www.pref.hokkaido.lg.jp/kz/rkr/korona.htm" target="_blank" rel="noopener">http://www.pref.hokkaido.lg.jp/kz/rkr/korona.htm</a><br />今般の新型コロナウイルス感染症により影響を受ける事業主、労働者の方向けの、相談窓口や各種支援措置をお知らせします。'
        }
      ]
    }
  },
  head() {
    return {
      title: '企業の皆様・はたらく皆様へ'
    }
  }
}
</script>
<style lang="scss" scoped>
.Worker {
  &-Heading {
    @include font-size(30);
    font-weight: normal;
    color: $gray-2;
    margin-bottom: 12px;
  }
}
a {
  @include text-link();
}
</style>
