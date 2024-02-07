<script>
    import Accordion from "./Accordion.svelte";
</script>

<div class="flex mt-20 px-20 justify-between items-center gap-32">
    <div class="col-lg-6 mb-3 text-center inline-flex flex-col gap-6 items-center text-slate-700">
        <h2 class="text-4xl whitespace-nowrap">Brief Introduction about<br/>eBooks you will read</h2>
        <p>Coming-soon!!!</p>
    </div>
    <div class="flex flex-col gap-4" id="accordionExample">
        <Accordion title="Rara And The Queen's Gown" body={`<strong class="text-green-500">Rara And The Queen's Gown</strong> Lorem ipsum dolor sit, amet consectetur
            adipisicing elit. Modi, dolor? Laudantium eveniet ducimus obcaecati dignissimos
            doloribus exercitationem modi totam fugiat? Illo facere quo voluptate ipsa esse
            praesentium, asperiores, ratione, sed maiores fugit suscipit ipsam pariatur quis cum
            amet deleniti consequuntur Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Laborum fugiat sit veniam provident. Eligendi doloremque, exercitationem aut earum et
            repudiandae!`} isCollapse={false} />
        <Accordion title="Flesh and Steel in the Camp" body={`<strong>Flesh and Steel Camp.</strong>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. At excepturi in hic quod
            pariatur non minus nihil sed obcaecati cupiditate expedita voluptates, eius eveniet
            aliquid laboriosam distinctio, voluptatibus quisquam. Velit doloribus sit veritatis
            provident culpa, autem voluptatum labore nemo aut. Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Iste, earum?`} />
        <Accordion title="Why I Told Her?" body={`<strong>Why I Told her?.</strong> Lorem, ipsum dolor sit amet consectetur adipisicing
            elit. Excepturi omnis officia soluta magnam itaque ad fuga, incidunt dicta rem accusamus
            illum repellat perspiciatis distinctio nulla vitae explicabo ducimus debitis sunt nisi
            vero adipisci accusantium? Cum a velit numquam delectus cumque!. Lorem, ipsum dolor sit
            amet consectetur adipisicing elit. Ipsa aperiam in nostrum commodi fugit repellat sit ea
            laborum quibusdam reiciendis!`} />
    </div>
</div>