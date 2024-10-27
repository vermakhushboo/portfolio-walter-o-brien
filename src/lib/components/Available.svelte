<script>
    import { Typography, Button } from '@appwrite.io/pink-svelte';
    import { IconLinkedin, IconGithub } from "@appwrite.io/pink-icons-svelte";
</script>

<section id="available" class="container">
    <Typography.Title size="medium">
        <span>●</span>
        Available for new projects now
    </Typography.Title>

    <Typography.Text variant="l-500">Available for new partnerships and collaborations. Let's chat!</Typography.Text>

    <div class="social-buttons">
        <Button.Button variant="secondary" size="medium">
            <IconLinkedin />
            LinkedIn</Button.Button>
        <Button.Button variant="secondary" size="medium">
            <IconGithub />
            GitHub
        </Button.Button>
    </div>
</section>

<style>
    span {
        color: var(--color-bgcolor-success);
    }

    .social-buttons {
        display: flex;
        flex-direction: column;
        width: 100%;
        gap: 0.5rem;
    }
</style>
