<script>
    import { House, Lightning, PlusCircleDotted, Funnel, Search } from "svelte-bootstrap-icons";
</script>

<div class="d-flex flex-column align-items-stretch flex-shrink-0 bg-body-tertiary" style="width: 380px;">
    <a href="/" class="d-flex align-items-center flex-shrink-0 p-3 link-body-emphasis text-decoration-none border-bottom">
        <h1><Lightning height={32} width={32} /> QSA</h1>
    </a>
    <h2 class="px-3 pt-3">Data</h2>
    <ul class="nav nav-pills flex-column p-3">
        <li>
            <a href="/data/insert" class="nav-link link-body-emphasis">
                <PlusCircleDotted height={16} width={16} />
                Insert data
            </a>
        </li>
        <li>
            <a href="/data/manage" class="nav-link link-body-emphasis">
                <Funnel height={16} width={16} />
                Manage data
            </a>
        </li>
        <li>
            <a href="/data/query" class="nav-link link-body-emphasis">
                <Search height={16} width={16} />
                Query data
            </a>
        </li>
    </ul>
    <h2 class="p-3">Dashboards</h2>
    <div class="list-group list-group-flush scrollarea">
        <a href="/dashboard/example" class="list-group-item list-group-item-action active py-3 lh-sm" aria-current="true">
            <div class="d-flex w-100 align-items-center justify-content-between">
                <strong class="mb-1">List group item heading</strong>
                <small>Wed</small>
            </div>
            <div class="col-10 mb-1 small">Some placeholder content in a paragraph below the heading and date.</div>
        </a>
        <a href="/dashboard/example-active" class="list-group-item list-group-item-action py-3 lh-sm">
            <div class="d-flex w-100 align-items-center justify-content-between">
                <strong class="mb-1">List group item heading</strong>
                <small class="text-body-secondary">Tues</small>
            </div>
            <div class="col-10 mb-1 small">Some placeholder content in a paragraph below the heading and date.</div>
        </a>
    </div>
</div>