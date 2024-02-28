<script>
    import {defineCustomElements} from "@salable/stencil-library/loader";

    defineCustomElements();
</script>

<main class="flex min-h-screen flex-col gap-8 p-24">
    <h1>Salable Web Components Svelte Demo</h1>
    <salable-pricing-table
            api-key="s1tVhRx3WH2jUm2cWTl8g6dbNj7GJ8Zg21XuzEds"
            uuid="0b8fc07d-6707-491a-ad6e-1828d57fe1cc"
            global-success-url="https://example.com/success"
            global-cancel-url="https://example.com/cancel"
            global-grantee-id="123"
            member="456"
    ></salable-pricing-table>
</main>
