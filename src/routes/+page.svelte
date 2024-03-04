<script>
    import {defineCustomElements} from "@salable/web-components/loader";

    defineCustomElements();
</script>

<main class="flex min-h-screen flex-col gap-8 p-24">
    <h1>Salable Web Components Svelte Demo</h1>
    <h2>Pricing Table</h2>
    <salable-pricing-table
            api-key="test_19fda9530350e27eb3948749d511c9d51d09e7c5"
            uuid="44363fe3-2607-437a-8b66-5375d7a762a2"
            global-success-url="https://example.com/success"
            global-cancel-url="https://example.com/cancel"
            global-grantee-id="example-grantee-123"
            member="example-member-123"
    ></salable-pricing-table>
    <h2>Checkout</h2>
    <salable-checkout
            api-key="test_19fda9530350e27eb3948749d511c9d51d09e7c5"
            plan-uuid='390fe44d-33d9-48fc-9863-eb641e148249'
            member='example-member-123'
            grantee-id='example-grantee-123'
            success-url="https://example.com/success"
    ></salable-checkout>
</main>
