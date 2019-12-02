<template>
<div>
    <nav class="breadcrumb" aria-label="breadcrumbs">
    <ul>
        <li><a href="#" class="has-text-info">Bulma</a></li>
        <li><a href="#" class="has-text-info">Documentation</a></li>
        <li><a href="#" class="has-text-info">Components</a></li>
        <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
    </ul>
    </nav>
    <div class="box has-background-info has-text-left">
        <div class="content">
            <h1 class="has-text-white">Hello, Admin.</h1>
            <p class="has-text-white">Hope you are having a great day</p>
        </div>
    </div>
    <div class="columns">
        <div class="column">
            <div class="box">
                <div class="content">
                    <h3>439K</h3>
                    <p class="has-text-grey">Users</p>
                </div>
            </div>
        </div>
        <div class="column">
            <div class="box">
                <div class="content">
                    <h3>59K</h3>
                    <p class="has-text-grey">Products</p>
                </div>
            </div>
        </div>
        <div class="column">
            <div class="box">
                <div class="content">
                    <h3>3.4K</h3>
                    <p class="has-text-grey">Orders</p>
                </div>
            </div>
        </div>
        <div class="column">
            <div class="box">
                <div class="content">
                    <h3>19</h3>
                    <p class="has-text-grey">Exceptions</p>
                </div>
            </div>
        </div>
    </div>
    <div class="columns">
        <div class="column">
            <nav class="panel">
            <p class="panel-heading has-text-left has-text-grey">
                Events
            </p>
            <a class="panel-block is-active">
                Loream Ipsum dolem aire
                <!-- <b-button class="is-positioned-right">Button</b-button> -->
            </a>
            <a class="panel-block">
                Loream Ipsum dolem aire
            </a>
            <a class="panel-block">
                Loream Ipsum dolem aire
            </a>
            <a class="panel-block">
                Loream Ipsum dolem aire
            </a>
            
            <a class="panel-block">
                View-all
            </a>
            </nav>
        </div>
        <div class="column">
            <nav class="panel">
            <p class="panel-heading has-text-left has-text-grey">
                Inventory Search
            </p>
            <div class="panel-block">
                <p class="control has-icons-left">
                <input class="input" type="text" placeholder="Search">
                <span class="icon is-left">
                    <i class="fas fa-search" aria-hidden="true"></i>
                </span>
                </p>
            </div>
            </nav>
            <nav class="panel">
            <p class="panel-heading has-text-left has-text-grey">
                User Search
            </p>
            <div class="panel-block">
                <p class="control has-icons-left">
                <input class="input" type="text" placeholder="Search">
                <span class="icon is-left">
                    <i class="fas fa-search" aria-hidden="true"></i>
                </span>
                </p>
            </div>
            </nav>
        </div>
    </div>
</div>
</template>