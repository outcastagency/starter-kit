<template>
    <section :class="fields.classes">
      <div class="row">
        <BaseRichText v-if="fields.body" classes="richtext" :content="fields.body"></BaseRichText>
      </div>
    </section>
</template>

<script>
export default {
    name: 'sectionDefault',
    props: ['fields']
}
</script>