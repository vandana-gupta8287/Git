<div class="tablenoborder">
	<table cellpadding="4" cellspacing="0" summary="" id="request-constructing__table-basic-request-elements" frame="hsides" border="1" rules="all">
		<caption>
			<span class="tablecap">
				<span class="table--title-label">Table 1. </span>Requesting a Route
			</span>
		</caption>
		<colgroup>
			<col style="width:28.57142857142857%">
				<col style="width:28.57142857142857%">
					<col style="width:42.857142857142854%">
					</colgroup>
					<thead>
						<tr class="&#39;&#39;">
							<th class="cellrowborder" id="d156249e37">Element</th>
							<th class="cellrowborder" id="d156249e40">Value</th>
							<th class="row-nocellborder" id="d156249e43">Description</th>
						</tr>
					</thead>
					<tbody>
						<tr class="&#39;&#39;">
							<td class="cellrowborder" rowspan="2" headers="d156249e37 ">Base URL</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>
									<span class="keyword">https://apis.mappls.com/advancedmaps/v1/</span>
								</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Production environment</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 ">Authorization</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>
									<span class="keyword">"assigned_REST_license_key"</span>
								</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">The REST API license key authorized to access the resource</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" rowspan="3" headers="d156249e37 ">Resources</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to calculate an optimized route & its duration without considering traffic conditions.</td>
						</tr>
						<tr class="&#39;&#39;">
							<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization_eta</code>	
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to get an optimized route considering live traffic; Applicable for India only “region=ind” and “rtype=1” is not supported. This is different from <code>trip_optimization_traffic</code>; since this doesn't search aggresively for a route considering ONLY traffic, but it also takes into account the road classification & preferred paths as well. 
							</td>
						</tr>
						<tr class="&#39;&#39; override_background">
                        	<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization_traffic</code>	
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to search for routes considering live traffic; Applicable for India only “region=ind” and “rtype=1” is not supported 
							</td>
							</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 " rowspan="4">Profile</td>
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>driving</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for car routing
							</td>
						</tr>
                        <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>biking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for two-wheeler routing. Routing with this profile is restricted to <code>trip_optimization</code> or <code>trip_optimization_traffic</code>. <code>region</code> & <code>rtype</code>  request parameters are not supported in two-wheeler routing.
							</td>
						</tr>
            <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>walking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for pedestrian routing. Routing with this profile is restricted to <code>trip_optimization</code> only. <code>region</code> & <code>rtype</code>  request parameters are not supported in pedestrian routing.
							</td>
						</tr>            
            <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>trucking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for Truck routing. Routing with this profile is restricted to <code>trip_optimization</code> or <code>trip_optimization_eta</code>. <code>region</code> & <code>rtype</code>  request parameters are not supported in truck routing.
							</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 ">Coordinates</td>
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>
							        "start and destination coordinates"
							    </code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">The coordinates pairs on which route is to be calculated. Minimum two pairs needed.
							</td>
						</tr>
					</tbody>
				</table>
			</div>

<br>













## Constructing the request URL

<div class="tablenoborder">
	<table cellpadding="4" cellspacing="0" summary="" id="request-constructing__table-basic-request-elements" frame="hsides" border="1" rules="all">
		<caption>
			<span class="tablecap">
				<span class="table--title-label">Table 1. </span>Requesting a Route
			</span>
		</caption>
		<colgroup>
			<col style="width:28.57142857142857%">
				<col style="width:28.57142857142857%">
					<col style="width:42.857142857142854%">
					</colgroup>
					<thead>
						<tr class="&#39;&#39;">
							<th class="cellrowborder" id="d156249e37">Element</th>
							<th class="cellrowborder" id="d156249e40">Value</th>
							<th class="row-nocellborder" id="d156249e43">Description</th>
						</tr>
					</thead>
					<tbody>
						<tr class="&#39;&#39;">
							<td class="cellrowborder" rowspan="2" headers="d156249e37 ">Base URL</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>
									<span class="keyword">https://apis.mappls.com/advancedmaps/v1/</span>
								</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Production environment</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 ">Authorization</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>
									<span class="keyword">"assigned_REST_license_key"</span>
								</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">The REST API license key authorized to access the resource</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" rowspan="3" headers="d156249e37 ">Resources</td>
							<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to calculate an optimized route & its duration without considering traffic conditions.</td>
						</tr>
						<tr class="&#39;&#39;">
							<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization_eta</code>	
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to get an optimized route considering live traffic; Applicable for India only “region=ind” and “rtype=1” is not supported. This is different from <code>trip_optimization_traffic</code>; since this doesn't search aggresively for a route considering ONLY traffic, but it also takes into account the road classification & preferred paths as well. 
							</td>
						</tr>
						<tr class="&#39;&#39; override_background">
                        	<td class="cellrowborder" headers="d156249e40 ">
								<code>trip_optimization_traffic</code>	
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">to search for routes considering live traffic; Applicable for India only “region=ind” and “rtype=1” is not supported 
							</td>
							</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 " rowspan="4">Profile</td>
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>driving</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for car routing
							</td>
						</tr>
                        <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>biking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for two-wheeler routing. Routing with this profile is restricted to <code>trip_optimization</code> or <code>trip_optimization_traffic</code>. <code>region</code> & <code>rtype</code>  request parameters are not supported in two-wheeler routing.
							</td>
						</tr>
            <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>walking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for pedestrian routing. Routing with this profile is restricted to <code>trip_optimization</code> only. <code>region</code> & <code>rtype</code>  request parameters are not supported in pedestrian routing.
							</td>
						</tr>            
            <tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>trucking</code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">Meant for Truck routing. Routing with this profile is restricted to <code>trip_optimization</code> or <code>trip_optimization_eta</code>. <code>region</code> & <code>rtype</code>  request parameters are not supported in truck routing.
							</td>
						</tr>
						<tr class="&#39;&#39; override_background">
							<td class="cellrowborder" headers="d156249e37 ">Coordinates</td>
							<td class="cellrowborder" headers="d156249e40 ">
							    <code>
							        "start and destination coordinates"
							    </code>
							</td>
							<td class="row-nocellborder" headers="d156249e43 ">The coordinates pairs on which route is to be calculated. Minimum two pairs needed.
							</td>
						</tr>
					</tbody>
				</table>
			</div>

<br>