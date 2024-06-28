<template>
    <ContentPage>
        <div class="content">
            <Adsense
                ins-style="display: block;height: 150px; width: 100%"
                style="max-height: 150px;"
                data-ad-client="ca-pub-3283982605864712"
                data-ad-slot="5250489226"
                data-ad-format="horizontal">
            </Adsense>
            <HistoryTable />
        </div>
    </ContentPage>
</template>

<script>
import ContentPage from '@/components/page/ContentPage';
import HistoryTable from '@/components/history/HistoryTable';
export default {
    name: 'HistoryPage',
    components: {
        HistoryTable,
        ContentPage,
    },
};
</script>
