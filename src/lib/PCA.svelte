<script>
    import { PCA } from 'ml-pca';

    let data = new Array(10).fill(new Array(3).fill(0));
    data = data.map(x => x.map(y => Math.random()));

    const pca = new PCA(data);

</script>