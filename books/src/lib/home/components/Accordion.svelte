<script>
    import Icon from "@iconify/svelte";

    export let isCollapse = true;
    export let title = "";
    export let body = "";

    const toggleAccordion = () => {
        isCollapse = !isCollapse;
    }
</script>

<div class="rounded-lg shadow-md text-slate-700 overflow-hidden">
    <button on:click={toggleAccordion} class="font-medium flex items-center justify-between text-xl p-4 shadow-sm w-full text-left " type="button">
        {title}
        <Icon icon="uil:angle-down" class="transform transition-all duration-500 {!isCollapse ? "rotate-180" : ""}" width="24" height="24" />
    </button>
    <div class="overflow-hidden transition-all duration-500 px-4 {isCollapse ? "py-0 max-h-0" : "p-4 max-h-56"}">
        {@html body}
    </div>
</div>