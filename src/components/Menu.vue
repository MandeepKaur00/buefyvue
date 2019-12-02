<template>
    <b-menu class="has-text-left"> 
                <b-menu-list label="GENERAL">
                  <b-menu-item  label="Dashboard"></b-menu-item>
                  <b-menu-item label="Customers"></b-menu-item>
                  <b-menu-item label="Others"></b-menu-item>
                </b-menu-list>
                <b-menu-list label="ADMINISTRATION">
                  <b-menu-item label="Team Settings"></b-menu-item>
                  <b-menu-item>
                    <template slot="label">Administrator</template>
                    <b-menu-item  label="Member"></b-menu-item>
                    <b-menu-item  label="Plugin"></b-menu-item>
                    <b-menu-item  label="Add a Member"></b-menu-item>
                    <b-menu-item  label="Remove a Member"></b-menu-item>
                  </b-menu-item>
                  <b-menu-item  label="Invitations"></b-menu-item>
                  <b-menu-item  label="Cloud Storage Enviornment Settings"></b-menu-item>
                  <b-menu-item label="Authentication"></b-menu-item>
                  <b-menu-item  label="Payments"></b-menu-item>
                </b-menu-list>
                <b-menu-list label="TRANSACTIONS">
                  <b-menu-item  label="Payments"></b-menu-item>
                  <b-menu-item  label="Transfer"></b-menu-item>
                  <b-menu-item label="Balance"></b-menu-item>
                  <b-menu-item  label="Reports"></b-menu-item>
                </b-menu-list>
              </b-menu>
</template>