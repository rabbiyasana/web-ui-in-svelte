<script>
let count = 0;
const incriment =()=>{
    count+=1;
}
</script>

<button on:click={incriment}>
clicked me
</button>
<p>
{count === 1 ? "time" : "times"}
{count}
</p>