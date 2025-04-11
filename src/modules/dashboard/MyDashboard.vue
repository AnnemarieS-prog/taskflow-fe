<script setup lang="ts">
    import {
        Card,
        PageContent,
        PageTitle
    } from '@/components';

    import { useTranslation } from '@/composables';

    const { t } = useTranslation();
</script>

<template>
    <PageTitle :name="t('dashboard')" :show-back-button="false" />

    <PageContent>
        <Card>
            <!--TODO: insert list component here-->
            * insert list here *
        </Card>
    </PageContent>
</template>

<style scoped></style>