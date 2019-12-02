<template>
    <b-navbar>
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Bulma Admin
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item href="#">
                <strong>Home</strong>
            </b-navbar-item>
            <b-navbar-item href="#">
                <strong>Orders</strong>
            </b-navbar-item>
            <b-navbar-item href="#">
              <strong>Payment</strong>
            </b-navbar-item>
            <b-navbar-item href="#">
              <strong>Exceptions</strong>
            </b-navbar-item>
            <b-navbar-item href="#">
              <strong>Reports</strong>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>