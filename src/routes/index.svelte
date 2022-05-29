<script context="module">
   export async function load({ url }) {
      const nurl = new URL(url)
      nurl.searchParams.append('foo', 'bar')
      return {}
   }
</script>
