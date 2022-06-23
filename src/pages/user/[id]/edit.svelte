<script>
  import { params } from '@roxi/routify';

  export let id;
  
  console.log('enter page: /user/1/edit')
  console.log('referencing id in <script> is ok', id)
</script>

{console.error('access from markup', {
  // 'access id in markup': id, // <-- trigger calls to this page before leaving to parent page
  '$params.id':$params.id // 
  })||''}


<a href="/user">Go to /user</a><br>
<a href="/user/1/view">Go to /user/1/view</a><br>
