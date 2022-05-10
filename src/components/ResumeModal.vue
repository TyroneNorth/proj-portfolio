<script setup lang="ts">
import Button from './Button.vue';

</script>

<template>


<!-- Modal -->
<div class="row">
    <div class="col-lg-12">
        <div class="modal fade" id="resumeModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-xl">
            <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Contact Form</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
                <img src="https://via.placeholder.com/300x300" alt="">
            </div>
            <div class="modal-footer">
                <a label="Close" class="outline-btn" type="button" data-bs-dismiss="modal">Close</a>
                <a label="Save changes" class="ghost-btn" type="submit">Save Changes</a>
            </div>
            </div>
        </div>
        </div>
    </div>
</div>
</template>

<style>

</style>