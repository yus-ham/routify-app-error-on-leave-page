<script>
  import { params } from '@roxi/routify';

  console.log('enter page: /user/1/view')
</script>

{console.error('access from markup', {
  '$params.id':$params.id // 
  })||''}


<a href="/user">Go to /user</a><br>
<a href="/user/1/edit">Go to /user/1/edit</a><br>
