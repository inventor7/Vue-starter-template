<template>
    <ClientLayout>
        <h1 class="  text-center " >Home Page</h1>
        <p>Home page content</p>

        {{ $t('hello') }}

        <select v-model="$i18n.locale">
            <option value="en">en</option>
            <option value="ar">ar</option>
        </select>
    </ClientLayout>
</template>

<script setup>

</script>
