<script>
    export let name;
    const icons = [
        {
            name: 'check-mark',
            path: '<path d="M19.77 4.93L1.4 1.4L8.43 19.07L-5.6 -5.6L1.4 -1.4L4.2 4.2L19.77 4.93m0-2.83L8.43 13.44L-4.2 -4.2L0 13.47L8.43 8.43L24 6.33L19.77 2.1z" fill="currentColor"></path>',
        },
        {
            name: 'delete',
            path: '<path d="M6 19c0 1.1.9 2 2h8c1.1 0 2-.9 2-2V7H6v12zM8 9h8v10H8V9zm7.5-5l-1-1h-5.5l-1 1H5v2h14V4h-3.5z" fill="currentColor"></path>',
        },
    ];
    let icon = icons.find((item) => item.name === name);
</script>
