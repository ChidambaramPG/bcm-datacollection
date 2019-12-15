<template>
  <div class="card-box">
    <div class="table-responsive">
      <div class="row table-row">
        <div class="col-md-12">
          <h5 class="table-title border-bottom" >Your additions</h5>
          <table class="table table-hover">
            <thead class="table-head">
              <tr>
                  <th>BC#</th>
                <th>Card</th>
                <th>Status</th>
                <th>Added By</th>
                <th>Action</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                  <td>
                      12334
                  </td>
                <td>
                  <img
                  class="card-img img-responsive"
                  src="../../../assets/img/card.jpg"
                />
                </td>
                <td>
                    <span class="badge badge-danger ">Not Edited</span>
                </td>
                <td></td>
                <td>
                  <!-- <a href=" " ></a> -->
                  <button class="btn btn-danger" @click.prevent="()=>showDeleteBrochureModal()"><i class="fas fa-times" /> Delete</button>
                </td>
              </tr>
              <tr>
                  <td>
                      12334
                  </td>
                <td>
                  <img
                  class="card-img img-responsive"
                  src="../../../assets/img/card.jpg"
                />
                </td>
                <td>
                    <span class="badge badge-success ">Edited</span>
                </td>
                <td>Subin M</td>
                <td>
                  <!-- <a href=" " ></a> -->
                  <button class="btn btn-danger" @click.prevent="()=>showDeleteBrochureModal()" disabled><i class="fas fa-times" /> Delete</button>
                </td>
              </tr>
              <tr>
                  <td>
                      12334
                  </td>
                <td>
                  <img
                  class="card-img img-responsive"
                  src="../../../assets/img/card.jpg"
                />
                </td>
                <td>
                    <span class="badge badge-success ">Edited</span>
                </td>
                <td>Subin M</td>
                <td>
                  <!-- <a href=" " ></a> -->
                  <button class="btn btn-danger" @click.prevent="()=>showDeleteBrochureModal()" disabled><i class="fas fa-times" /> Delete</button>
                </td>
              </tr>
              <tr>
                  <td>
                      12334
                  </td>
                <td>
                  <img
                  class="card-img img-responsive"
                  src="../../../assets/img/card.jpg"
                />
                </td>
                <td>
                    <span class="badge badge-success ">Edited</span>
                </td>
                <td>Subin M</td>
                <td>
                  <!-- <a href=" " ></a> -->
                  <button class="btn btn-danger" @click.prevent="()=>showDeleteBrochureModal()" disabled><i class="fas fa-times" /> Delete</button>
                </td>
              </tr>
              
              
              
            </tbody>
          </table>
        </div>
      </div>
    </div>
    <div class="row pagination-row">
      <nav aria-label="Page navigation page-nav">
        <ul class="pagination justify-content-center">
          <li class="page-item">
            <a class="page-link" href="#" aria-label="Previous">
              <span aria-hidden="true">&laquo;</span>
              <span class="sr-only">Previous</span>
            </a>
          </li>
          <li class="page-item"><a class="page-link" href="#">1</a></li>
          <li class="page-item active"><a class="page-link" href="#">2</a></li>
          <li class="page-item"><a class="page-link" href="#">3</a></li>
          <li class="page-item">
            <a class="page-link" href="#" aria-label="Next">
              <span aria-hidden="true">&raquo;</span>
              <span class="sr-only">Next</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
    name:'CardsList'
}
</script>

<style scoped>
table {
  border-top: none;
  font-size: 14px;
}

th {
  font-weight: 400;
}
.table-title {
  padding: 10px;
}

.table-head {
  background-color: #f95473;
  color: white;
}
.pagination-row{
  padding-top:10px;
  
}
nav{
  width:100%;
}

li.page-item>a{
  color:#f95473;
  background-color:white;
}
li.page-item.active>a{
  color:#f95473;
  background-color: #212b5e;
  border-color: transparent;
}
.card-img{
    width:100px;
}
</style>
