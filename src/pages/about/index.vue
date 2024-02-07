<template>
        <div>
                <Cart />
                <ClientLayout>
                        <h1>Home Page</h1>
                        <ms-account-box style="font-size: 2em; color: red" />
                        {{ t('hello') }}
                        {{ locale }}

                        <select v-model="locale">
                                <option value="en">en</option>
                                <option value="ar">ar</option>
                        </select>
                </ClientLayout>
        </div>
</template>
    
<script setup>
import { useI18n } from 'vue-i18n'
const { t, locale } = useI18n()

</script>
    
    