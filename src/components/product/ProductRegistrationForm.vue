<template>
	<div class="site-container">
		<div class="container-fluid">
			<div class="site-snb">
				<ul class="nav nav-pills">
					<li role="presentation" class=""><a href="상품관리_01목록.html">목록</a></li>
					<li role="presentation" class=""><a href="상품관리_02상세.html">상세</a></li>
					<li role="presentation" class="active"><a href="상품관리_03등록.html">등록</a></li>
					<li role="presentation" class=""><a href="상품관리_04수정.html">수정</a></li>
				</ul>
			</div>
			<!-- //site-snb -->
			<div class="page-header">
				<h1 class="h2 font-weight-light">상품관리</h1>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">표시설정</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">진열상태</th>
								<td colspan="3">
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="productProgress" id="productProgress_y" value="option1"/><i></i></span> 진열함
									</label>
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="productProgress" id="productProgress_n" value="option2" checked/><i></i></span> 진열안함
									</label>
								</td>
							</tr>
							<tr>
								<th class="active">판매상태</th>
								<td colspan="3">
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="sellState" id=" sellState_y" value="option1"/><i></i></span> 판매함
									</label>
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="sellState" id="sellState_n" value="option2" checked/><i></i></span> 판매안함
									</label>
								</td>
							</tr>
							<tr>
								<th class="active">상품분류 선택</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<select class="form-control">
												<option value="">대분류</option>
												<option value="">여성</option>
												<option value="">남성</option>
											</select>
										</div>
										<div class="input-group">
											<select class="form-control">
												<option value="">중분류</option>
												<option value="">여성복</option>
												<option value="">실크액세서리</option>
											</select>
										</div>
										<div class="input-group">
											<select class="form-control">
												<option value="">소분류</option>
												<option value="">여성</option>
												<option value="">남성</option>
											</select>
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">메인진열</th>
								<td colspan="3">
									<table class="table table-bordered">
										<colgroup>
											<col style="width:100px;" />
											<col />
											<col style="width:100px;" />
											<col />
										</colgroup>
										<tbody>
											<tr>
												<th class="active">추천상품</th>
												<td>
													<label class="checkbox-inline"> <input type="checkbox" /> 진열함 </label>
												</td>
											</tr>
											<tr>
												<th class="active">신상품</th>
												<td>
													<label class="checkbox-inline"> <input type="checkbox" /> 진열함 </label>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">기본 정보</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">상품명</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">모델명</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">상품코드</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">상품상태</th>
								<td colspan="3">
									<div class="input-group">
										<select class="form-control">
											<option value="">신상품</option>
											<option value="">중고상품</option>
											<option value="">반품상품</option>
											<option value="">재고상품</option>
											<option value="">전시상품</option>
										</select>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">상품 요약설명</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">상품 간략설명</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
									<div class="xs-mt-5">- 상품의 간단한 추가 정보를 입력할 수 있습니다.</div>
								</td>
							</tr>
							<tr>
								<th class="active">상품 상세설명</th>
								<td colspan="3">
									<div>
										<div style="padding:200px;background-color:skyblue;text-align:center;">에디터</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">검색어설정</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
									<div class="xs-mt-5">- 검색어는 ', (콤마)'로 구분해주시기 바랍니다.</div>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">판매 정보</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">소비자가</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="number" value="0" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
										KRW
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">공급가</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="number" value="0" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
										KRW
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">판매가</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="number" value="0" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
										KRW
									</div>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">이미지 정보</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">이미지 등록</th>
								<td colspan="3">
									<div class="row">
										<div class="col-xs-2 input-file-box">
											<input type="file" id="input-file-now" class="dropify" data-height="200" data-default-file="" data-allowed-file-extensions="jpg png gif" />
											<div class="xs-mt-5">
												상세 이미지<br />
												권장사이즈 000x000
											</div>
										</div>
										<div class="col-xs-2">
											<input type="file" id="input-file-now" class="dropify" data-height="200" data-default-file="" data-allowed-file-extensions="jpg png gif" />
											<div class="xs-mt-5">
												목록 이미지<br />
												권장사이즈 000x000
											</div>
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">추가 이미지 등록</th>
								<td colspan="3">
									<div class="hidden">
										<div class="col-xs-2 input-file-box model">
											<input type="file" data-height="100" data-default-file="" />
											<button class="btn btn-xs btn-danger btn-remove"><i class="fa fa-times" aria-hidden="true"></i><span class="sr-only">삭제</span></button>
											<button class="btn btn-xs btn-primary btn-duplicator"><i class="fa fa-plus" aria-hidden="true"></i><span class="sr-only">추가</span></button>
										</div>
									</div>
									<div class="row">
										<div class="col-xs-2 input-file-box">
											<input type="file" class="dropify" data-height="100" data-default-file="" />
											<button class="btn btn-xs btn-primary btn-duplicator"><i class="fa fa-plus" aria-hidden="true"></i><span class="sr-only">추가</span></button>
										</div>
									</div>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">제작 정보</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">제조사</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="text" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">공급사</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="text" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">제조일자</th>
								<td colspan="3">
									<div class="col-sm-12">
										<div class="row">
											<div class="form-inline">
												<div class="input-group">
													<div data-min-view="2" data-date-format="yyyy-mm-dd" class="input-group date datetime date-width-default" data-link-field="dtp_input1">
														<input size="16" type="text" value="" readonly="" class="form-control" />
														<span class="input-group-addon input-group-addon-transparent"><span class="glyphicon glyphicon-th hide"></span><i class="fa fa-calendar" aria-hidden="true"></i></span>
													</div>
												</div>
											</div>
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">출시일자</th>
								<td colspan="3">
									<div class="col-sm-12">
										<div class="row">
											<div class="form-inline">
												<div class="input-group">
													<div data-min-view="2" data-date-format="yyyy-mm-dd" class="input-group date datetime date-width-default" data-link-field="dtp_input1">
														<input size="16" type="text" value="" readonly="" class="form-control" />
														<span class="input-group-addon input-group-addon-transparent"><span class="glyphicon glyphicon-th hide"></span><i class="fa fa-calendar" aria-hidden="true"></i></span>
													</div>
												</div>
											</div>
										</div>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">원산지</th>
								<td colspan="3">
									<div class="input-group">
										<select class="form-control">
											<option value="">프랑스</option>
											<option value="">독일</option>
										</select>
									</div>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">배송 정보</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:100px;" />
							<col />
							<col style="width:100px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">배송방법</th>
								<td colspan="3">
									<div class="input-group">
										<select class="form-control">
											<option value="">택배</option>
											<option value="">퀵배송</option>
											<option value="">화물배송</option>
										</select>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">배송지역</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="text" value="전국지역" name="" id="" class="form-control input-sm width-default text-right" />
										</div>
										에 배송가능
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">배송기간</th>
								<td colspan="3">
									<div class="form-inline">
										<div class="input-group">
											<input type="number" value="3" name="" id="" class="form-control input-sm width-sm text-right" />
										</div>
										일 ~
										<div class="input-group">
											<input type="number" value="7" name="" id="" class="form-control input-sm width-sm text-right" />
										</div>
										일 정도 소요됩니다.
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">배송비 설정</th>
								<td colspan="3">
									<div class="input-group">
										<select class="form-control">
											<option value="">배송비 무료</option>
											<option value="">고정배송비 사용</option>
											<option value="">구매금액에 따른 부과</option>
											<option value="">구매금액별 차등 배송료 사용</option>
										</select>
									</div>
								</td>
							</tr>
							<tr>
								<th class="active">배송비 상세 설정</th>
								<td colspan="3">
									<table class="table table-bordered">
										<colgroup>
											<col style="width:100px;" />
											<col />
											<col style="width:100px;" />
											<col />
										</colgroup>
										<tbody>
											<tr>
												<th class="active">구매 금액</th>
												<td>
													<div class="form-inline"><input type="number" value="50000" name="" id="" class="form-control input-sm width-sm text-right" />원 미만</div>
												</td>
												<th class="active">배송비</th>
												<td>
													<div class="form-inline"><input type="number" value="50000" name="" id="" class="form-control input-sm width-sm text-right" />원</div>
												</td>
											</tr>
										</tbody>
									</table>
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
					<h4 class="lead">검색엔진 최적화</h4>
					<table class="table table-bordered">
						<colgroup>
							<col style="width:200px;" />
							<col />
							<col style="width:200px;" />
							<col />
						</colgroup>
						<tbody>
							<tr>
								<th class="active">검색엔진 노출 설정</th>
								<td colspan="3">
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="sellState" id=" sellState_y" value="option1"/><i></i></span> 노출함
									</label>
									<label class="radio-inline">
										<span class="form-radio"><input type="radio" name="sellState" id="sellState_n" value="option2" checked/><i></i></span> 노출안함
									</label>
								</td>
							</tr>
							<tr>
								<th class="active">브라우저 타이틀 : Title</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">메타태그1 : Author</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">메타태그2 : Description</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">메타태그3 : Keywords</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
							<tr>
								<th class="active">상품 이미지 Alt 텍스트</th>
								<td colspan="3">
									<input type="text" name="" id="" class="form-control input-sm" />
								</td>
							</tr>
						</tbody>
					</table>
					<!-- //table -->
				</div>
			</div>
			<div class="row">
				<div class="col-sm-4 text-left"></div>
				<div class="col-sm-4 text-center">
					<a class="btn btn-default" href="상품관리_01목록.html" role="button"><i class="fa fa-times" aria-hidden="true"></i> 취소</a>
					<a class="btn btn-success" href="상품관리_02상세.html" role="button"><i class="fa fa-check" aria-hidden="true"></i> 등록</a>
				</div>
				<div class="col-sm-4 text-right"></div>
			</div>
		</div>
		<!-- //container-fluid -->
	</div>
</template>
<script>
// $(document).ready(function() {
// 	alert(5);
// });
</script>
