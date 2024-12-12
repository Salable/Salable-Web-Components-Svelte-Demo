<script>
    import {defineCustomElements} from "@salable/web-components/loader";

    defineCustomElements();
</script>

<main class="flex min-h-screen flex-col gap-8 p-24">
    <h1>Salable Web Components Svelte Demo</h1>

    <h2>Pricing Table</h2>
    <salable-pricing-table
            session-token="YOUR_SESSION_TOKEN"
            uuid="YOUR_PRICING_TABLE_UUID"
            global-success-url="https://example.com/success"
            global-cancel-url="https://example.com/cancel"
            global-grantee-id="example-grantee-123"
            member="example-member-123"
            currency="GBP"
    ></salable-pricing-table>

    <h2>Checkout</h2>
    <salable-checkout
            session-token="YOUR_SESSION_TOKEN"
            plan-uuid="YOUR_PLAN_UUID"
            member='example-member-123'
            grantee-id='example-grantee-123'
            success-url="https://example.com/success"
            currency="GBP"
    ></salable-checkout>

    <h2>Subscription Invocies</h2>
    <salable-invoices class="theme" session-token="YOUR_SESSION_TOKEN" subscription-uuid="YOUR_SUBSCRIPTION_UUID" limit="3"></salable-invoices>
</main>
